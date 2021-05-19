# Instructions for creating new repositories

This repository should intentionally remain as a private repo, so therefore is not published on an external github.io page. 
Upon following the instructions below, the repo will automatically run integration tests, spelling checks and page building tests. 

To create a new repository in this format, follow the instructions outlined below:

- Create an empty repository on Github, `my-repo` then clone it locally.
- On local machine type `git checkout -b gh-pages` to create a gh-pages branch for your new repository, `my-repo`
- Clone **this** repo `ichec-template` (i.e. the repo you want to copy) **OUTSIDE** your new local repo and make sure that the gh-pages branch is checked out.
- On local machine force remove the `.git` folder in the newly created `ichec-template`. This makes it a normal folder rather than a git repo
- **IMPORTANT:** Ensure that `.github/*` and `.gitignore` are present. The former folder contains the CI needed for the pages to build
- Copy the contents of `ichec-template` into your empty repo (`cp -r ichec-template/* new-repo`)
- Now in `new-repo`, locally add all untracked files using `git add .`
- Next, commit using `git commit -m "copied from ichec-template"` to add everything to the repo. The message itself can be edited.
- To push the new branch to GitHub, type `git push origin gh-pages`
- Set `gh-pages` to be the default branch for the repo on GitHub through; Settings -> Branches. Find the switching arrows icon and select gh-pages from the drop down icon.
- Enable `github.io` page building through Settings -> Pages. You may need to set the theme first time. The theme choice will not matter as it will be forced into the Carpentries style. 
- Copy the link and paste into About, on the right hand side of the main page.
