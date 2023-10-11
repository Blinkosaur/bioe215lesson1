Lesson 1: Computational project organization

Project workflows
Bryan (2017)

- What problems can setwd() cause in your scripts and how do RStudio projects address them?
1) the setwd() file paths only work for the author and it is unlikely to work later in the
2) The project is not self-contained and portable. 
3) Difficult to switch between projects and/or work on multiple projects at the same time

- When you call rm(list=ls()), what is removed from your environment? 
It only deletes user-created objects from the global workspace

- What’s left over that restarting your R session would remove? 
1) packages that have been loaded are still available. 
2) anything that has been set to non-default values remain  
3) Working directory is the same 

- What’s the keyboard shortcut for restarting your R session?
Command+Shift+F10 

--------------------------------------------------------------------------------
Version control
You either read Bryan (2018) or Braga et al. (2023). Answer the questions for the paper you read.

Bryan (2018)

The basic git commands are commit, push, and pull. Which commands change happen locally (i.e., on your computer)? 
- ....commit....

Which happen remotely?
- pulll...push

Why do diffs work for source code (e.g., .R files) but not Word documents (i.e., .docx files)?

"If a file is binary, such as a Word document or Excel spreadsheet, you will not get human-readable diffs anyway, nor can GitHub display the content in the browser. Binary files are also a reliable source of merge conflicts (see below), because they are beyond the reach of Git's sophisticated automatic merging logic. A large binary file that changes often is, therefore, the worst of all worlds. This implies that adoption of Git/GitHub suggests a pivot away from .docx, .xlsx, and .pdf as primary file formats and toward .Rmd, .md, and .csv, at least during periods of rapid development."


Why is Markdown useful for GitHub repos?
1) "Any file written in Markdown is rendered in an HTML-like way on GitHub. In particular, formatting and links “just work.” This is the last piece we need to seal my claim that merely pushing your project to GitHub gives it a web presence for zero extra work"
2)" If you make even a modest effort to embed a few explanatory Markdown files in your repo, you will get an automatically updated project website for free. In particular, if a directory has a README.md file, GitHub renders it like a home page or “index.html” when people visit that directory in the browser"
3) "This provides a lightweight system for exposing work-in-progress to collaborators, without slowing down to create separate reports. Comment lines that begin with #' are elevated to top-level prose, providing a way to make the document more welcoming for a reader."


