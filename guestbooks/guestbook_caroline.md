# Universal Decompositional Semantics (UDS) and Child Speech

## Caroline Gish | cng18@pitt.edu

**My project repo:** <https://github.com/Data-Science-for-Linguists-2022/UDS-child-speech>

**The overall plan for my project:** [project plan](https://github.com/Data-Science-for-Linguists-2022/UDS-child-speech/blob/main/project_plan.md)

**How the project is coming along so far**: [progress report](https://github.com/Data-Science-for-Linguists-2022/UDS-child-speech/blob/main/progress_report.md)

---

### Alejandro's Notes
This is an extremely interesting research project. I am extremely impressed at the data (and very surprised that it's free) and I think you will do amazing with it. I also am surprised to learn just how varied childhood linguistic development research can get as I assumed it would mostly be geared towards only the psychological side of things. However, I am a bit confused about what exactly you will be doing in the project. If I understand correctly from reading your `project_plan.md`, the bulk of your project is analyzing the dataset itself and highlighting the tools that came along with it. Could you add specific research questions with this?

> Thanks, Alejandro! I, too, am not *exactly* sure what I will ultimately do with the project :) I'm still working through the UDS dataset and the toolkit that comes with it which is a large component of my project.

### Ben's Notes
I think this is a very interesting project; I had never heard of
these data sets before and they look to have a lot of information within them.
If I had one critique, it would be that due to the complex nature of the project,
I would add some description of what the UDS data set contains and how it can be used,
as I was initially a bit confused by it.

> Thanks, Ben! It took me a while initially to figure out what UDS was too, and I'm still figuring it out! There is a paper that goes along with it that I linked from my project plan file, but I should also write up a summary about the UDS dataset (or at least something about it) to go along with the other stuff in my repo.

### Misha's Notes:
- **One thing I liked:** Excellent topic. Child Language Development is a really rich topic! It is a great contribution to apply well developed analytical frameworks to new data so I'm interested to see what you find about implementing that with the Child speech data. Additionally Decompositional Semantics are fascinating (I assume there's some pustejovsky in there somewhere) in how qualia make up our understanding of similar words having very different meanings based on context.

- **One thing to consider:** I'd be interested to know a little bit more about the implications/stakes/hypotheses of the UDS framework as it pertains to child speech data. what do you anticipate that your analysis will bear regarding child speech in comparison to the original data?

- **One thing I learned:** I learned about another model of Decompositional Semantics, so that's always exciting. The coding seems intense! I would give pustejovsky's qualia theory a look if you haven't gotten the chance before.

> Thanks for your comments, Misha! For my presentation and final project submission, I am hoping to include a write-up from my own perspective, informed by the original UDS  paper, about the implications of the UDS framework pertaining to other types of language datasets. I would have liked to look into this more, but, yeah, the UDS dataset / decomp toolkit threw me for quite a loop, so I wasn't able to do exactly what I originally envisioned. 

### Rohan's Notes:

- **One thing I liked:** Your project is fascinating! I really like the idea of taking two datasets that study different things and examining them through the context of the other one. I hope you get all your data figured out, I think the analysis should be fascinating!

- **One thing that could be improved:** Your initial exploration notebook was really interesting, but it sometimes felt like a little too much was being printed. There were several point where I had to scroll through pages on pages of data to get to the next analysis, so it could be a little cleaner.

- **One thing I learned:** The existence of the UDS and CHILDES datasets! The CHILDES one sounds particularly interesting, I'm really excited to see what you do with it.

> Thanks for the feedback, Rohan! I also didn't know about the existence of either one of these datasets before I started this project!

### Tianyi's Notes:

- **One thing I liked:**
I really like the depth of your project plan.
You seem to have a good idea of the data exploration that you plan to do prior to starting your analysis, which is of course a very good thing.
Like others have said, it's very interesting that you're not only analyzing a dataset but specifically analyzing it within the context of another dataset.

- **One thing that could be improved:**
In `hicks_initial_exploration.ipynb`, I think it'd be best for you to leave out most of the printed data, as a small sample would suffice.
In `uds_initial_exploration.ipynb`, most of the Python code blocks were never run, so I'm not sure what the output is meant to be (I'm guessing it's due to the error in the first code block, though).

- **One thing I learned:** I think it's interesting that not only such datasets exist but also that the UDS organizes its data into a graphical format.

> Thank you, Tianyi! I started out with a decently solid plan, but it has been a struggle to do what I wanted to do with the UDS dataset because it is so massive and comes with its own toolkit. I have now fixed the thing that was causing the error in loading the dataset and toolkit!

### Man Ho's Notes:

- **One thing I liked:**
I am so happy to find out another CHILDES project! I like your idea of analysing CHILDES data with UDS dataset and toolkit.

- **One thing that could be improved:**
The error you got in your `childes_exploration.ipynb` when you were trying to get the code tier was probably caused by an utterance (likely utterance 303) which does not have a code tier. There could be more utterances missing code tiers and you may need to add a conditional statement in your list comprehension so that you can escape the error. In 'semi-pseudocode', you could try something like this:
```
cod_tier = [u.tiers['%cod'] for u in hicks_utterances if '%cod' in u.tiers.keys()]
```
I guess you can then ignore the utterances without code tiers in your analysis.

- **One thing I learned:**
It seems like the UDS dataset and decomp toolkit could be useful for me as well! I am not sure if I will have enough time to try them out in my project though...

> Thanks Man Ho! Your code suggestion was helpful and appreciated, and I was able to successfully access the code tier. It's annoying that some of the utterances don't have the code tier, though, since that's what I am interested in!

### Kinan's Notes:
- **One thing I liked:**
  First off the hand waving thing on the README.md is soooo cute how did you do that. But actually speaking I really like the Data, Analysis, and Presentation part of your project in the Project Plan, it is very easy to follow and helps me follow whats going on with the other files. Your README.md directory is also very helpful in understanding what is where and what is what.

- **One thing that could be improved:**
  i think in your notebooks you could section things off more clearly? sometimes the outputs and the descriptions blend in together towards the end but also it could just be a work in progress. not a big deal at all.

- **One thing I learned:**
  CHA files!!!



### Emma's Notes:
- **What was done well:** Even in the project plan, you seem to have a very solid understanding of the data you're working with and what your end goal is for the analysis.  I like that you detailed all of the issues you had when working with the dataset--hopefully your frustration will be worth it, and some fortunate soul will stumble upon your progress report when trying to figure out the UDS data for themselves!
- **What could be improved:** It might be nice to add a little description of each notebook to your README, just so its clear which notebook is for what, and in what order your created them (or intend someone to view them).
- **One thing I learned:** I feel like a lot of people are working with very idiosyncratic file types, like CHA files here! I know you mentioned having separate code and data licenses, but I hadn't really considered including tool licenses (like for pylangacq).
