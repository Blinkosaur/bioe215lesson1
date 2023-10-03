You were (probably) exposed to a lot of new material in this lesson. In this part of the assessment, you’ll create a cheat sheet for yourself. Create a markdown file called docs/proj_org_notes.md. In that file, create a short document you can use to guide you when you create your next analysis project. Consider which steps only need to be configured once versus which have to be repeated for every project. If there were steps you found counterintuitive or confusing today, make a note of why you did them or how you figured them out.


Steps to Do Every time 
- Make a folder to house everything 
- In that folder put folders for all project subcategories (data, paper, docs, figs, etc.)
- Use the folder system instead of setwd thingy and also restart R using the R things in the folder where you are working not by just clicking on the RStudio icon (I think...)

When you Make a Thing that Should go to the Githubs:
- Go to Git Tab over to the top right ---> 
- Click the boxes of things you want to move to the internets (?)
- "Commit" & make a comment to remind yourself what it is
- "Push"

Things to do sometimes I think: 
- Ask for a token by putting: usethis::create_github_token() in the terminal
- This opens Github and gives you a code
- In the console put: gitcreds::gitcreds_set()
    - this prompts you to put in your token code, press enter and now RStudio & Github are connected

Things I found confusing: 
- Why do I want to make a website for my R-ing? 

