# [UN PARALLEL CORPORA ANALYSIS](https://github.com/Data-Science-for-Linguists-2022/UN-Parallel-Corpora-Analysis)
### Kinan Al-Mouk, Na-Rae Han, March 15th 2022

## Thank You!!

#### Emma's Entry:
3-17-2022
- **What was done well:** I really liked the organization of the README. This made it super easy to get acquainted with all the files (and the links made it easy to find them!). The jupyter notebook is also super organized, with links to each section!
- **What could be improved:** There are a few typos in analysis section of the project plan--these just make it look a little less professional. I think the jupyter notebook could also benefit from a little blurb at the beginning (of the file and each large section) explaining what the code does.
- **What I learned:** Looking at the three graphs, I'm surprised to see that Mandarin has such low values comparatively for sentence length, sentence tokens, and word tokens.  I suppose this makes sense, since Chinese orthography is group by syllable and the other five languages write in more phoneme-like segments.  I also learned that I need to get on reorganizing my repository because, *shucks*, this looks good!

#### Caroline's entry (2022-03-17)

I think I'm writing this literally as you are making changes to your various files lol so hopefully things still make sense!

- **What was done well:** I'm seeing that Emma already mentioned this, but your *README.md* looks great! I think this is how we're supposed to organize it by the end of the project, but not a lot of us have gotten around to doing it yet, so it looks impressive. Likewise, your main notebook is well-organized.

- **Possible improvements:** This could be too nitpicky, but I think it would be easier to read and Better Practice to not have the titles of the data sources and the various languages highlighted as if they are code in your *markdown* files. Also, maybe it's just that you haven't fully gotten around to this yet, but I think that your *UN_Data_Analysis.ipynb* could benefit from more prose explanations / commentary alongside the code. It's nice to see what people are thinking as I look through their code!

- **One thing I learned:** I haven't yet seen anyone print out the time it took to load data or complete a task. This is something that we didn't tend to focus on in Comp Ling, but it's important from a more engineering side of things. Since you struggled with the sheer amount of data and things timing out / dying, I assume the time it took for everything to load in and process must have been high up in your mind!

## Alejandro's Notes
I don't know much about the _United Nations_, so I would've assumed they would have more than only 6 official languages. Nevertheless, an extremely interesting research project, and I absolutely love your repository's organization. I also appreciate how well-kept the `README.md` is and how all files in the repository serve a purpose and are given a clear explanation for their existence. However, I was wondering if you could specify more so the research you plan on doing. You mention analyzing things like hapaxes and TTR and other linguistic features, but what do you plan to do with these things in-context? Also, how do you plan to communicate what exactly the differences are between different language translations?

## Ben's Notes
I really liked your README file - it made it simple to get a high-level overview of your project's structure.
One improvement could be some more info in the data gathering notebook - for example, why you chose the
dataframe layout that you did.
One thing I learned was the official languages of the UN - I would have assumed it was those of the security council,
but it was cool to see Spanish and Arabic there as well!

## Tianyi's Notes

- **What was done well**: I know that pretty much everyone else has said this already but your README is incredibly organized, and I appreciate the quick description of each file in the repo.

- **What could be improved**: I think some commentary added between code blocks would help users understand why you decided to do certain things such as timing the reading of each UN language file.
Also, I think you could probably do a bit more with some of the provided measures; for example, since you had said that you wanted to analyze hapax legomena, you could count the number of hapaxes for each language using frequency dictionaries.

- **What I learned**: Mandarin appears to have drastically different values for every provided measure.
I can understand why for most of them, but I think it may have been in part due to how the text was tokenized.
For example, in the little snippet of the word tokens that I can see in `UN_Data_Analysis.ipynb` it looks like "1994年5月17日安全理事会" ("Security Council of May 17, 1994") is being treated as one token while I would've personally tokenized it as `["1994年", "5月", "17日", "安全", "理事会"]`.

## Man Ho's Notes

- **What was done well**: You looked at the data carefully and figured out that there was a parsing problem for Mandarin. You also switched to SpaCy (which we just learned in the class) to fix that problem.

- **What could be improved**: Like what other folks said above, the parsing of Mandarin words was wrong because of the nature of Chinese orthography: each character represents a syllable (and generally a morpheme; sometimes a part of a morpheme). Besides, there are no space between two words. Therefore, NLTK simply parse the whole phrase/sentence separated by punctuations as one word/token. SpaCy was doing a proper job here.  
However, I found another problem due to this orthography issue: in `SpaCyNLP.ipynb`, you are slicing the first 1000 characters (incl. punctuation):
`mandarin_samp = mandarin100[:1000]`
The problem is, as I said, each Chinese characters is a morpheme or a syllable. Therefore, the information contained in this 1000 character-slice is different from, say, what you got from English (which is just the first 1000 letters (incl. some punctuations)). You may run into a similar problem for Arabic which uses abjad alphabet (so one character is probably one syllable, unlike in English where one character is just one letter).

- **What I learned**:  SpaCy performs very well on parsing Mandarin. I will try SpaCy first if I need to work on Mandarin data in the future!
