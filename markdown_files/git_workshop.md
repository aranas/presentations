---
title: "Wrap-up"
output: revealjs::revealjs_presentation
reveal_plugins: ["notes"]
---

## Golden Git rules

* <span style="color:rgba(251, 69, 23)">push</span> often
* <span style="color:rgba(251, 69, 23)">pull</span> before add (avoid 'empty' merge commits)
* if undoing, <span style="color:rgba(251, 69, 23)">git status</span> first
* Write <span style="color:rgba(251, 69, 23)">descriptive</span> commit messages

# When git goes wrong...

##

<img src="images/git_conflict2.jpeg" height="400">


## Reset

<span style="color:rgba(251, 69, 23)">git checkout &ndash;&ndash; &lt;file&gt;</span> to undo local changes

<span style="color:rgba(251, 69, 23)">git reset HEAD &lt;file&gt;</span>  to unstage (undo add) a file

<span style="color:rgba(251, 69, 23)">git reset HEAD^</span> to undo your latest commit

##

<img src="images/terminal_gitstatus.png" height="600" style="background:none; border:none; box-shadow:none;">

##

<img src="images/git_flow.png" height="400" style="background:none; border:none; box-shadow:none;">

## Reset

* <span style="color:rgba(251, 69, 23)">git status</span> to check what you have locally
* <span style="color:rgba(251, 69, 23)">git reflog</span> to find commit number
* <span style="color:rgba(251, 69, 23)">git reset --soft commit#</span> to reset local state
* <span style="color:rgba(251, 69, 23)">git reset --hard commit#</span> &#128680; to dismiss local state

##

git reset --soft commit#/HEAD^ <img src="images/git_flow_resetsoft.png" height="400" style="background:none; border:none; box-shadow:none;">

##
<img src="images/gitpushforce.jpg" height="400">

## Rebasing

* <span style="color:rgba(251, 69, 23)">git rebase</span> changes **your** git history!
* <span style="color:rgba(251, 69, 23)">git rebase -interactive</span> to clean you **local** branch history before merging

##

<img src="images/pull.png" height="600" style="background:none; border:none; box-shadow:none;">

##

<img src="images/rebase.png" height="600" style="background:none; border:none; box-shadow:none;">

# Where to go next?

## Learn more! {data-background-iframe="https://learngitbranching.js.org/" style="position: absolute; width: 50%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;"}

## Practice makes perfect 💪

Start using Git version control

# Code (Git IDE integration)

## Integrated Development Environment

* Matlab > R2014b
* Pycharm, Spyder
* RStudio
* (atom)

## Matlab
<video height="600" controls>
  <source src="media/matlab_gitintegration.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

## Pycharm

<img src="images/Pycharm-git.png" height="600" style="background:none; border:none; box-shadow:none;">

## RStudio

<img src="images/Rstudio-git.png" height="400" style="background:none; border:none; box-shadow:none;">


# Text Documents{data-background="./images/typing_pic.jpg"}

##

<img src="images/word_binary.png" height="600" style="background:none; border:none; box-shadow:none;">

## Git + Markdown + Pandoc {data-background-iframe="https://pandoc.org/index.html" style="position: absolute; width: 50%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;"}

<img src="images/giticon.png" height="100" style="background:none; border:none; box-shadow:none;"><img src="images/markdown_cover.png" height="100" style="background:none; border:none; box-shadow:none;">

##

<img src="images/atom_markdown.png" height="600" style="background:none; border:none; box-shadow:none;">

<div class="notes">
Keep content and form separated. For Manuscript this means, if you update figures you don't have to re copy-paste them into word
</div>

## Why bother?

<span style="color:rgb(250,87,40)">**Flexibility**</span>
separating content & form

<span style="color:rgb(250,87,40)">**Peace of mind**</span>
rewrite without regrets

<span style="color:rgb(250,87,40)">**Reproducibility**</span>
remember feedback related changes

<span style="color:rgb(250,87,40)">**Collaboration**</span>
ask for feedback through pull requests

## Atom text editor

<video height="600" controls>
  <source src="media/atom_gitintegration.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

# Slides{data-background="./images/presenting_pic.jpg" style="color:black;"}

## Git + (pandoc + revealjs)

pandoc -t revealjs -s -o outputfile<span style="color:rgb(250,87,40)">.html</span> inputfile<span style="color:rgb(250,87,40)">.md</span>

<a href="https://github.com/hakimel/reveal.js/">git clone https://github.com/hakimel/reveal.js/</a>

Publish your slides through <a href="https://github.com/aranas/presentations">GitHub Pages</a>

## Web-based {data-background-iframe="https://openscience-nijmegen.nl/" style="position: absolute; width: 40%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;"}

  You can easily embed other web content and interact live


# Project management{data-background="./images/projectman_pic.jpeg"}

##

* Issues <a href="https://github.com/Radboud-University/osc-nijmegen/issues/52">(example: this workshop!)</a>
* Pull requests
* Milestones
* Project boards <a href="https://github.com/unicef/magicbox">(example: UNICEF magicbox)</a>
* Wiki <a href="https://github.com/guard/guard/wiki">(example: guard)</a>

<!-- Note:
assignees, labels, commit -m "fixes \#12", interactive check boxes
wikis can be -->

# Thanks

##

<img src="images/keepcalmandgit.jpg" height="500">
