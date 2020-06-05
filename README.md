# Sub Ripper
*Ripping subs from Netflix and creating a clean transcript*

I made this for my own personal language learning study. I've been watching *Pokemon Sun and Moon* on Netflix in German, and now I want to study the transcripts so I can rewatch and understand even more!

**Instructions for Use:**
1. Follow [this tutorial](https://forum.videohelp.com/threads/382919-How-to-extract-Netflix-subtitles) to rip the subtitles file from your desired episode and save as an `.xml` file.
2. Use the subtitle converter of your choice to generate a `.csv` file. I went with [this one](https://gotranscript.com/subtitle-converter) that allows for conversion from `.xml` to `.csv`.
3. Use the code below to convert it all to a nice, simple `.txt` file.
4. Study the transcript however you prefer!

**Notes:**
- This will not help you with the names of characters for a "full" transcript unless the original subtitles incldue the character names. That's just the data available. If you find a cool way to do it with the video data and ML, I'd love to see it.
- Be sure to save your `.csv` with a file name that makes sense for general purpose use. Then be sure to edit the `re.sub()` lines toward the bottom of this code to reflect your unique naming conventions. (Tip: If you abbreviate, be sure the abbreviation wouldn't be found in the words of your target language... Or else you'll have a hard time.)
- This guide is intended for personal use only.
