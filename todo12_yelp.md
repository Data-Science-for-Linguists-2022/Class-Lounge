# To-do 12: Poking at Big Data (Yelp)

## Na-Rae the fake student:
- My 4-year-old ThinkPad laptop did ok! It has ... RAM, which worked ok with this much data, etc. Grepping through the whole of xxx json file took...

## Kinan:
- My Macbook which I got when I thought I was going to be a polisci major is traumatized from switching to CS. Downloading it only took 10 minutes suprisingly. I believe a supercomputer or just a PC designed for processing data would do this a lot better, this todo was a lot of sitting and waiting for things to process. My computer sounded like a Spirit flight. I learned that patience is a virtue with big data and that if I want to continue working with large data sets (which I am doing for my term project) I need to start considering what computers I should purcahse beforehand. 

## Alejandro
- I did this todo on my desktop because it runs Ubuntu 20.04.4 LTS as its OS\*. The command line stuff I was already pretty familiar with. However, things got interesting once I ran the `process_reviews.py` script. I got it to work at 10000000 entries and it was insane. At that many entries, it used all its 62GiB of RAM\* and about 10GiB from its swap space, which caused my entire PC to slow down tremendously at that point. I tried running the script on the full dataset, it was able to fully create the dataframe, but the `Counter()` function completely annihiliated any and all RAM and swap space. As for CPUs, for some reason, it really hated CPU6 and mostly used that.

\*Before you say "that's too much RAM," I didn't buy it with that much RAM. The company I ordered my PC from made a mistake and gave me *way* more RAM than I had specified, but I'm not complaining. It allowed me to do this afterall.
\*I really enjoy it and working on my desktop is easier than using my laptop, which struggles with even opening my web browser (10 minutes if not pre-prepped).