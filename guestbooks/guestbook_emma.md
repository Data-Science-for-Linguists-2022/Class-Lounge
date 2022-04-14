# A Linguistic Look Inside Outsider Music
Emma McKibbin | ECM68@pitt.edu

**Check out the project repository [here](https://github.com/Data-Science-for-Linguists-2022/Outsider-Music-Linguistic-Analysis)!**

If you'd like to see where the project is headed, check out the [project plan](https://github.com/Data-Science-for-Linguists-2022/Outsider-Music-Linguistic-Analysis/blob/a98ea1330bc40dfa15581c55f29e8cda1a39df0d/project_plan.md).  If you'd like to see where the project is at, check out the [progress report](https://github.com/Data-Science-for-Linguists-2022/Outsider-Music-Linguistic-Analysis/blob/a98ea1330bc40dfa15581c55f29e8cda1a39df0d/progress_report.md).

---

## Caroline's entry (2022-03-17)

I think we're all finding each other's projects to be super interesting, but I will reiterate and say that this is a very interesting project! I'm looking forward to seeing what you find out from a data-driven analysis as opposed to simply a human reading through the lyrics / knowing about the artists and doing more of a informal, qualitative analysis.

- **What was done well:** This is a rather small detail, but one that makes your project repo / project in general much more approachable upon first encounter - I like that you have updated your *README.md* to include a brief project summary. I haven't gotten around to doing this yet, but it's a reminder that I need to! Additionally, the commentary and explanations that accompany your code are well done. I like that when I am looking at your code and the output, I can follow your thought process from when you yourself were encountering the output.

- **Possible improvements:** Small thing to "improve" - the link to *load_json_to_df.ipynb* in your *progress_report.md* is broken. Just letting you know so you can go back and see what's up!

- **One thing I learned:** I didn't realize there was a package to go along with lyrics from Genius. I'm always surprised and fascinated to find out that if you want to do something, someone has probably already created a tool for you to do so! Super cool.

***Thank you!  I'm hoping to add a bit more to my README to make the project even easier to navigate (along with fixing those links!). --Emma***

## Ben's Notes
As a fan of outsider music, I really love your project idea!
I think you have a very clear research question and data acquisition strategy.
I liked how you acknowledged potential problems with the data, like the high number of songs
by Wesley Willis, which could skew the data.
One possible improvement could be to pick a license, as the project currently has an empty `LICENSE.md` file.

***Thanks!  I may try to collect more data or just excerpt Wesley Willis's discography to fix that skew.  And thank you for the license reminder! --Emma***

## Alejandro's Notes
Extremely interesting topic you picked! I had no idea there was an exact term for music made by beginners. As for the repository itself, I really like that your whole project seems very approachable and that you have your hypothesizes listed directly in your `project_plan.md`. For improvement, could you elaborate on how the classifier you mentioned would highlight the most important distincts between insider and outsider music, as well as how you plan to use those differences in linguistic analysis?

***Thanks, Alejandro!  I'm hoping to use the Naive Bayes model at this point, since it's transparent about the most informative features.  I'll make sure to include that explanation in my final repository, as you said! --Emma***

## Tianyi's Notes

- **One thing I liked:**
I think you did a very good job of clearly conveying the purpose of your project and defining necessary to your potential audience (myself included) in your project plan.

- **One thing that could be improved:**
Could you elaborate on what features you plan to study for your analysis (syntax, vocabulary, etc.)?

- **One thing I learned:**
I didn't know that "outsider music" was even a term, so it's very interesting that you're studying this style (?) of music for your project.

***Thank you, Tianyi! Defining the exact nature of the analysis was exactly what I was having difficulty with during the project plan, since I wasn't entirely sure what this kind of data analysis would entail.  At the moment, I'm looking mostly into vocabulary, but you highlighted exactly the question I'm encountering at this stage! --Emma***

## Kinan's Notes
- **One thing I liked:**
  I tell you this all the time but your readme is very nice, the summary before the directory helps the readers understand WHY each file exists not only just what it is which can help more with applying knowledge tbh which i personally liked. I also like the script analysis python file I need to do something like this for reading in my data properly and processing it and its been stressing me out but this helps a lot.

- **One thing that could be improved:**
  Data samples folder only has one thing in it are you gonna add anything else?

- **One thing I learned:**
  I had no idea what Outsider music was so the defenition of that is something I learned. SPEAKING OF WHICH IT MIGHT BE COOL IF YOU COULD ATTACH A PLAYLIST OR SOMETHING SO PEOPLE COULD LIKE LISTEN TO A SONG AND LIKE FULLY BE IN IT

***Thank you, Kinan! I'm leaving my data samples folder limited for now, mostly because I am afraid of Genius.  I may upload an annotated pdf (or something similar) to  make it clearer how the JSON file is structured and what data I'm using here. Also, I will definitely have song demos for my presentation, but a playlist is a good idea! --Emma***

## Man Ho's Notes
- **One thing I liked:**
  I like how well organized your files are: you explained what each notebook does and how it is related to other notebook. I like the idea that you numbered your notebooks - this makes your repo so easy to follow!
  
- **One thing that could be improved:**
  I just have some minor suggestions:  
  In `3_data_cleaning_and_exploration.ipynb`, you have:  
```
i = 0
while i != len(df):
...
i = i+1
```
But I think a for loop is probably a bit more efficient (so in each iteration, you don't need to do `i = i+1` operation):
```
for i in range(len(df)):
...
```

Also, in this line `lyricsdf[lyricsdf.lyrics.duplicated()].tail(20)`, I think it's printing correctly the duplicated rows except the first occurance (e.g. printing only 2 entries out of 3 entries which have the same lyrics). Is that what you intended to print?

- **One thing I learned:**
Like other folks, I had no ideas what outsider music was! It's very interesting to look at how outsider music is different from other genres linguistically! By the way, I guess I am sort of like an 'outsider linguist' in this sense as I didn't have formal training in linguistics or computer science. Knowing that there are successful 'outsiders' is very encouraging!
