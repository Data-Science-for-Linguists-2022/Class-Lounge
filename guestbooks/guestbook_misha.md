# Russian Textbook Vocab Analysis
**Author**: Michael O'Brien
**Repo link**: [Textbook_Vocab_Analysis](https://github.com/Data-Science-for-Linguists-2022/Textbook_Vocab_Analysis)

## Kinan's Feedback
Hi Misha! I looked at your project and I am slighly lost a little. I know how you feel about getting lost in the data, my project is also giving me a really hard time with getting everything. Where the code didnt explain, your project plan did so thats really good. I like how its one of your goals to encode Cyrillic. I also like how you chose to go with Russian, the  thing i remember about when we first met was how interested you were in Russian langauge so I'm really excited to see the work you do with this. I would reccomend combining the two progress reports, unless its written somewhere that we shouldn't.

Hey Kinan, thanks for the suggestions and feedback. I found out that I can just copy and paste from the textbook pdfs into plain text so I'll be going low-fi for that bit to work it out :)

## Man Ho's Feedback

**One thing that was done well:** Getting the data and the permission for fair use

**One avenue for improvement or suggestion:** The error you got was probably caused by encoding error. You may try opening the file with "encoding specified". For example:  
`file = open(filename, encoding="utf8")`

You may need to check the type of encoding your file has.

**One thing I learned:** Reading and parsing non-latin letters are not straightforward...

Hello Man Ho, thank you for your feedback, yeah the packages I imported weren't tons of help, so like I responded to Kinan's comments, going low-fi this time!

## Emma's Feedback
3-21-2022
- **What was done well:** I was really impressed by how concrete your project plan is.  You've made your end goal very clear! I also appreciate that even with bumps in the road, you've kept a detailed log on the issues and your steps to approach them.
- **What could be improved:** You may want to include a sample of your raw data at this point.  Publishing a whole PDF would be infeasible, but there may be a sample page that's already public (i.e., preview on the selling page) that could be included.
- **One thing I learned:** I had previously been unaware of PDF text extraction packages.  When I read your project plan, my first thought was OCR, which seemed very daunting (to me at least). I'm impressed that you're working with tangible text data--that's an entirely different beast from a lot of the other projects. I hope that the pre-packaged PDF readers will work for you!

Hi Emma, thank you so much for your comments, I agree adding some preliminary data so others can see what's going on will be really useful! Now that I have a way to get my data into plain text, I think things will start to run more smoothly!

## Caroline's entry (2022-03-22)

- **What was done well:** The plan for your project is very well thought out, and the project itself is quite interesting. I look forward to seeing what you find out!

- **Possible improvements:** Along with your code that's returning an error, you could maybe include some commentary about what you were intending to do with the code or what you thought would happen. This often helps me think through what I need to do.

- **One thing I learned:** It's my first time hearing about "plumbing a PDF"!

Hello Caroline, your note about including comments is really great! there are times that I forget about that kind of stuff. It will make it easier for folks to offer suggestions to the code, so thank you!

## Alejandro's Feedback
I like this. I haven't really seen textual work that's in another language (let alone another script), so it's interesting to see how that has played out. Something that I like is that you have a very clear goal in mind and it seems very reasonable and manageable. However, I do think you can improve with your repository organization, `README.md`, and overall cleanliness of your Jupyter Notebooks. Something I learned is that Python has libraries for PDFs and PDF text extraction, I did not know that!

# Ben's Feedback
I liked your README; I think it provides a good overview of the project and your goals.
However, it could be improved by adding links to and descriptions of the files in your project.
One thing I learned is that there is a Russian National corpus.

## Rohan's Feedback
- **What was done well:** You really built your project around your dataset, and generally I think your plan was really solid! It made a lot of sense to me reading it.

- **Possible Improvements:** Your Jupyter Notebooks weren't really readable on my laptop, the printing of your data made my screen glitch up really badly for some reason. Besides that, I'm not really sure what your plans for analysis are. Your project seems very data-focused.

- **One thing I learned:** It is a lot harder to get text data out of a pdf than I would have though it would be.

## Tianyi's Feedback

- **One thing that was done well:** I really appreciate the detail that you put into your project plan and the commentary that you put into your progress reports.
It's good that you've been documenting your data processing journey in depth and being transparent about hurdles that you've run into.

- **One thing that could be improved:** I think it'd help if you could provide some commentary about some of the errors that you hit into your code.
Like Caroline said, something about what you were trying to do with the code would help.

- **One thing that I learned:** This is the first time that I've heard of automatic extraction of text from PDFs in python, and honestly it's really cool that you're working with that for your project.
I can definitely see this package as a potential starting point for some personal coding projects for myself.
