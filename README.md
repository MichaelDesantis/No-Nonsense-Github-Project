omg! all lines in this readme starting with "omg!" will be removed before final deployment and are notes for the video production. This is a test line to test the new url.

#The no nonsense GitHub Project. 
![alt tag](img/github_01.png) 
##A 1 hour no nonsense video tutorial series covering the basic usage of the worlds most popular version control software! 

Are you a self-taught Web or Software developer looking to take your first steps into the world of collaborative development? Or a coding bootcamp student looking to work on your first group project? Or perhaps you have simply never used GIT before and could use a crash course on how to use this software? If any of these apply to you, you've come to the right place.

I'm Michael Desantis! A Full-Stack web developer and Teachers Assistant at the Coding Bootcamp at UT Austin. In this video course I will be introducing the basics of GIT and GitHub (and no, they're not the same thing). I am creating this repository and README here to use as a handy reference guide to accompany the video material.

In this tutorial, you can watch and take notes. Or you can build a GitHub Repository of your own and follow along, pausing the videos as necessary. This course is structured in such a way where all the exercises build on the material from the previous videos. I highly recommend building a repository and following along step-by-step.  

The goal of this project is to provide you, the end user, with a brief, concise, and fast-paced instructional on how to use GIT. By the end of these videos, you should have a basic yet functional grasp and understanding of how to implement GIT in your development and projects. 

###Video 1 : Introduction to GIT and Version Control.
In this video, I'll be explaining the 5W's of GIT. What is Git? Why is it important? When should it be used? Who uses it? Where is it used? I'll also show you how to install and configure it for the first time. I'll be going over how to use it over the next 7 videos.  

#####Slides from video

#####Helpful Links

1. https://git-scm.com/download  (download page)
2. https://git-scm.com/book/en/v2/Getting-Started-Installing-Git  (installation guide)
3. https://help.github.com/articles/set-up-git/ (configure your local computer to match your GitHub account)
4. https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/ (ssh credentials, because re-entering your password each time is time consuming)
5. https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/ (git documentation on setting up ssh)

#####New GIT commands used

1. git --version  (tells you what version you have installed)
2. git config --global user.name "Your Name"  (configure username)
3. git config --global user.email yourname@example.com  (configure email)

###Video 2 : Building your first repository.
In this video, I'll guide you through building your first repository on your local computer. As well as how to connect it to GitHub. 

#####Slides from video

#####Helpful Links

1. https://help.github.com/articles/adding-a-file-to-a-repository-from-the-command-line/ (adding files from command line)

#####New GIT commands used

1. git init  (initialize git on local machine)
2. git remote add origin git@github.com:Username/Repository-Name  (connect your local repository to github)
3. git status  (see which files have been changed, and which ones you're adding)
4. git add fileName (track file, stage it for commit)
5. git commit -m "Your Message here" (commit your changes, attach a message, create save point)
6. git push origin master (send changes from your computer to GitHub)

###Video 3 : Your first collaborative exercise + basic workflow. 
In this video, I'll show you how to pull the latest changes from GitHub. How to fork and clone other peoples repositories. How to submit a pull request. And showing you a simple GitHub workflow. BONUS: learn how a gitignore file works! 

#####Slides from video

#####Helpful Links

1. https://help.github.com/articles/about-pull-requests/  (more detail on pull requests)
2. https://help.github.com/articles/fork-a-repo/ (don't worry if this seems a little advanced, we'll go into it in more detail in the upcoming videos)
3. https://help.github.com/articles/ignoring-files/ (using gitignore files in more depth)

#####New GIT commands used

1. touch .gitignore  (create .gitignore file)
2. git pull origin master  (pull latest changes from GitHub)
3. git remote -v  (view remote connections)

###Video 4 : All about branching.
video explanation text.
#####slides from video
#####Helpful Links
#####GIT commands used
omg! video topic: branching. changing branches, viewing branches, merging branches, deleting branches, why use branches.

#INTERMEDIATE VIDEOS START HERE.

###Video 5 : Dealing with merge conflicts, remote repositories, and developing as a team. 
video explanation text.
#####slides from video
#####Helpful Links
#####GIT commands used
omg! video topic: when multiple people develop as a team. git remote repositories, git url changes, git fetch, conflict resolution. deleting files. commit history vs file.

###Video 6 When things go wrong, and how to fix them.
video explanation text.
#####slides from video
#####Helpful Links
#####GIT commands used
omg! video topic: reverting changes, pulling previous versions, undoing commits, why commit messages matter.

###Video 7 : Git workflow 2.0, debugging and organizing larger GIT projects. 
video explanation text.
#####slides from video
#####Helpful Links
#####GIT commands used
omg! video topic: expanded git workflow. resolving issues with git diff. git rebase, remove a .git file.

###Video 8 Documenting your code, and GIT commands in depth.
video explanation text.
#####slides from video
#####Helpful Links
#####GIT commands used
omg! video topic: writing documentation. git tag, git log, git commandName --help, Why document your projects. Contribute to open source.
