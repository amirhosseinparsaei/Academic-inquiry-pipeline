# Academic-inquiry-pipeline

This pipeline helps students to automatically apply for their future positions using maximum capacity of their mail service with least effort.
My name is Amirhossein Parsaei M.D. and I am a researcher who is currently looking for a postdoc position. 
The process of finding emails of the related faculty and inquiring about the postdoc position I was looking for was a bit time consuming and demanded lots of effort.
That is why hereby I share my own pipeline that allowed me to automate the prcosses and helped me to send about 500 emails per day with a few clicks.

This repo has three parts:
  1. Email finder: This is a code that helps you automatically find and recieve the emails of faculty from your website of intreset.
  2. Draft creator: This is a guide and a googlesheets script that allows you to create those 500 drafts with 1 click.
  3. Draft sender: This is a script for googlesheets that allows you to automatically send all those drafts.

Notice:
- The process of finding emails may be one of the following:
- a. A website has all the names and emails in one single page. Then you can easily copy the whole page and ask chatgpt or another model to create a table from these names and emails.
- b. The website has a main page of faculty profiles list. In such websites the emails are usually not in the main page but are on the profile pages; either protected or non protected.
- c. The senario "b" but the main page comes in several pages like 10 or more. So there are several pages of hyperlinked names that are profile links.
- d. The senario "c" but the whole platform is no simply on HTML but is using JAVA and is simply like there is an interactive page that only works with clicks. In this case none of the profile links or page numbers have static address to extract, but rather those links are all dynamic.

  Currently the "Email finder" Only covers b and c (the a is easy to do). For senario d you have to use another method which I am currently workinng on.
  
Use and share. Please notice that any sort of misuse from this repo is your own responsibility.

**If you are new to any type of coding, proceed to rookie guide, Other wise proceed to codes.**
