---
language: bash
tags: git, work-flow, version control
type: lecture
resources: 0
---

## Ironboard - Lab Guide ##

This guide is meant as a reference that provides the detailed steps to go through when working on labs in Ironboard. You can come back to this reference later if you forget any of the steps below.

### 1. Fork ###

Forking is the process of making a personal remote copy of the Ironboard lab.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-1.png" alt="Git Workflow 1">

To get started, in Ironboard click the title of the lab to go to Flatiron School's copy of the lab on Github.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-0.jpg" alt="Ironboard Labs Step 0">

Next on Flatiron's Github Page for the lab click the Fork button.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-1.jpg" alt="Ironboard Labs Step 1">

Then select your personal Github account as the location to fork to.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-1b.jpg" alt="Ironboard Labs Step 1B">

### 2. Clone ###

Cloning is the process of making a local copy of the lab from your personal remote on Github. 

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-2.png" alt="Git Workflow 2">

To clone, click the copy button next to the Clone URL to copy it to your clipboard.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-2.jpg" alt="Ironboard Labs Step 2">

Next, in Terminal navigate to the parent directory where you would like to place this lab. Then type ♥ `git clone <paste the clone URL here>`  
Note: You should replace the &lt;paste the clone URL here&gt; including the &lt; and &gt; symbols in the snippet above with your actual clone URL by pressing command+v on mac or ctrl+v on windows. Example: git clone git@github.com:jongrover/html-album-cover-fe-004.git

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-2b.png" alt="Ironboard Labs Step 2b">

### 3. Work on the Lab ###

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-3.png" alt="Git Workflow 3">

Now we can work on the lab locally and even offline if we wish. Let's change directory into the folder for the lab ♥ `cd <lab-directory-name>`

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-2c.jpg" alt="Ironboard Labs Step 2c">

Then bring the lab up in Sublime text by typing ♥ `subl .`

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-2d.jpg" alt="Ironboard Labs Step 2d">

Follow the instructions in **README.md** file to complete the lab.

As you are completing your lab you may want to occassionally save your work by staging and committing files. To stage files in terminal type ♥ `git add <files or folders to add>` or you can also use this shortcut to stage all files in the current folder ♥ `git add .`

Then we can take a snapshot of those files by commiting our changes. To do so type ♥ `git commit -m "<message about what we did in this commit>"`  
Note: inside the quotes you want to put a message about what you did in this commit. Commit messages are conventionally in present tense. Something like: "add image to home page" or "finish contact form".

### 4. Push Your Work to Origin ###

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-4.png" alt="Git Workflow 4">

After adding and commiting your most recent work next we want to push our work up to our personal Github remote (origin). To push up to your remote type ♥ `git push <remote-name> <branch-name>`  
Note: The standard for labs would be to push to your (personal) remote named origin. By default you would push the work on your master branch. Example: ♥ `git push origin master`

### 5. Submit A Pull Request ###

Submitting a pull request can be described as the process of asking the maintainer of the Ironboard lab (upstream remote) to consider pulling (merging) in your work from your personal remote copy (origin remote). This enables your instructor to see your solution for the lab.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-5.png" alt="Git Workflow 5">

To do so, in Ironboard click the title of the lab to go to Flatiron Schools copy.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-0.jpg" alt="Ironboard Labs Step 0">

This will take you back to the Ironboard copy you originally forked from. Then click the Pull Requests link from the right sidebar.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4.jpg" alt="Ironboard Labs Step 4">

Next, click the New pull request button.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4b.jpg" alt="Ironboard Labs Step 4b">

Then click the compare across forks link.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4c.jpg" alt="Ironboard Labs Step 4c">

Then click the drop down menu for the head fork and select yourself from the list.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4d.jpg" alt="Ironboard Labs Step 4d">

After reviewing the comparison code and making sure it shows your solution, click the Create pull request button.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4e.jpg" alt="Ironboard Labs Step 4e">

Then click Create pull request button again.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4f.jpg" alt="Ironboard Labs Step 4f">

That's it your done! Now go back to Ironboard and click the Done with Lab button

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4g.jpg" alt="Ironboard Labs Step 4g">
