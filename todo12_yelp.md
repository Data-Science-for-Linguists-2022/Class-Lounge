# To-do 12: Poking at Big Data (Yelp)

## Na-Rae the fake student:
- My 4-year-old ThinkPad laptop did ok! It has ... RAM, which worked ok with this much data, etc. Grepping through the whole of xxx json file took...

## Kinan:
- My Macbook which I got when I thought I was going to be a polisci major is traumatized from switching to CS. Downloading it only took 10 minutes suprisingly. I believe a supercomputer or just a PC designed for processing data would do this a lot better, this todo was a lot of sitting and waiting for things to process. My computer sounded like a Spirit flight. I learned that patience is a virtue with big data and that if I want to continue working with large data sets (which I am doing for my term project) I need to start considering what computers I should purcahse beforehand.

## Alejandro
- I did this todo on my desktop because it runs Ubuntu 20.04.4 LTS as its OS\*. The command line stuff I was already pretty familiar with. However, things got interesting once I ran the `process_reviews.py` script. I got it to work at 10000000 entries and it was insane. At that many entries, it used all its 62GiB of RAM\* and about 10GiB from its swap space, which caused my entire PC to slow down tremendously at that point. I tried running the script on the full dataset, it was able to fully create the dataframe, but the `Counter()` function completely annihiliated any and all RAM and swap space. As for CPUs, for some reason, it really hated CPU6 and mostly used that.

\*Before you say "that's too much RAM," I didn't buy it with that much RAM. The company I ordered my PC from made a mistake and gave me *way* more RAM than I had specified, but I'm not complaining. It allowed me to do this afterall.
\*I really enjoy it and working on my desktop is easier than using my laptop, which struggles with even opening my web browser (10 minutes if not pre-prepped).

## Emma:
- For most of the more complex processes (e.g., untarring, processing smaller amounts of data), my computer sat at about 30% CPU usage and 50% memory usage.  My laptop is from 2019, with 16GB of RAM and the 8th gen Intel Core i7 (1.8-GHz clock speed), and it often fails to handle simple tasks, like turning the volume up or opening File Explorer.  So I was surprised it was able to handle up to 1,000,000 entries in the FOO.json!  However, at this large of a dataset, my memory usage shot up to 97% momentarily, then leveled out at 80% for the rest of processing, while my CPU usage maxed out at ~70%.  Shockingly, at that point, my computer did not sound like living next to the Presby heli-pad, but I didn't want to push it any further for fear of finding out what happened at 100% memory usage.  Given that the original "reviews" dataset had nearly 7M entries and that this was a fairly simple task, I can imagine that my personal computer would not be able to handle processing real "Big Data."

## Caroline

- I completed this To-do on my 2017 MacBook Pro which has been struggling a little bit recently, especially when I am working in the `<oXygen/>` IDE. Although, I am notorious for keeping a bajillion Chrome tabs open at the same time and not quitting out of my applications so I can see the notification icons, so that's not helping anything. My laptop has 8GB of RAM and the Intel Core i5 (3.1 GHz dual-core). When I downloaded the data set, I had only about 12GB of storage available total, so I downloaded the data set straight onto my external hard drive and figured out how to access it on the command line. It took all of 3 minutes to both download the compressed data and expand it which was must faster than I was expecting. I found the line/word/character count data about each of the JSON files all with one command, and my laptop struggled a bit to do this, with CPU usage up to 80% for the reviews JSON. As for processing the files, my laptop was processing up to 100,000 lines within a few seconds so I decided to bump up to 1,000,000 lines. This used pretty much all 8GB of RAM and 9-10GB from its swap space and took about 4 minutes. I wanted to see what would happen processing more lines, so I ran the script on 1,500,000 lines. The DataFrame took about 2 minutes and the rest took about 8 minutes for a total of 10 minutes. During this time, CPU usage was at 85% and memory usage was basically maxed out - the memory pressure bar was at its ceiling and consistently red. Saving a markdown file while this was running was a chore, but no weird sounds from my laptop! I'm not confident that my laptop would be able to process the dataset according to this Python script in its entirety, let alone in a more computationally demanding process.

## Tianyi

- I completed this To-Do on my 2017 MacBook Pro, which has a 2.3 GHz dual-core Intel i5 processor and 8 GB of RAM.
It was able to handle the dataset decently, and I was able to process up to 1 million lines.
As the number of lines climbed past 100,000, the runtime climbed past a few minutes, RAM usage got close to the 8-GB limit, and CPU usage occasionally spiked as high as 80%.
Once I reached 10 million, though, my computer was no longer able to process the data as the swap space completely occupied all remaining space on my hard drive.
With that in mind, clearly I'd need to increase my computer's RAM capacity and hard drive space in order to process any larger amounts of data.

## Ben

- I completed this on my Dell laptop, which has a 2.21 GhZ six-core Intel i7 and 16 GB of RAM.
I was able to do 1 million, with a max of ~34% CPU usage and 5.3 GB RAM usage (by Python).
I then tried 1.5 million, at which point I ran out of RAM and my PC froze.
If I had closed as many programs as possible, I likely could have done a bit more than 1 million.

## Man Ho

- My 8-year-old ThinkPad laptop did ok! It has 500 GB disk space, 12GB memory and 2.40 GHz Intel i3-4000M CPU. I could process 100,000 lines within seconds, but when I tried 1M, it took too long that I stopped running. The CPU usage went up to 50% and the RAM usage was increased by about 2 GB. I was using Edge browser with more than 10 tabs open though... My laptop was not frozen and I could still run other programs at the same time.

## Rohan

- Sorry this is late! I did not think to close everything out the first time I ran it, so with my usual 20-something tabs open in Chrome, Microsoft Word, Atom, Spotify, and Teams all open, I could run 1M files... but my computer's memory usage skyrocketed to 95%. It only took about three minutes though, and I could do other stuff while it was running.
- After I opened this file and saw that everyone else closed stuff out before they ran it, I tried again and got up to 10M before my memory completely filled up and my laptop started screaming at me. It took a good ten minutes to process though. Shockingly, even at this amount of processing, my CPU usage never went above 65% and stayed in the teens for most of the run-time, and neither of my GPUs heated up as much as I'm used to when I game.
- At 10M I finally got a memory error, which I was expecting seeing as I only have 15.4 GB of RAM. I'm shocked I could get it up that far honestly.
- Speaking of, my laptop stats! I used my HP Omen laptop, which is a little over a year old (I got it in December 2020). It has a 2.9 GHz dual-core AMD Ryzen processor and 16 GB of RAM (15.4 usable). It's a pretty hardcore gaming laptop, but the RAM and disk space were just not up to this amount of data.

## Misha
- Woof, this was something else. I don't really understand what it means to talk about these computer specs, but I'll just take everyone else's lead. I'm used an Asus Vivo laptop that's a couple years old with a four core 1.8GHz intel processor. I have 8GB of RAM. I felt very bad for my little computational son, who sat there whirring and doing his best. I definitely felt a lot of empathy for this machine. I too am struggling through a lot of work. I'm not really sure that I can comment on how to make things run better or smoother. But I agree that limiting other programs that are going to be taking up resources should be helpful!
