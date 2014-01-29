Alumni Office Application
=======
This is the repository we will be using for the moment

[Link to handy git guide](http://rogerdudler.github.io/git-guide/)

Everybody should run through the following for some quick 'n dirty git action

1. Clone the repository
  - `git clone git@github.com:btrebach/Alumni-Office-Application.git`
2. Create the file FirstnameLastname.txt
3. `git status` --> should show the file you just created
  - This shows the difference between the Working Directory (your computer) and the Index (staging area)
4. `git add FirstnameLastname.txt`
  - add: moves the file to the Index
5. `git commit -m 'FirstnameLastname initial commit'`
  - commit: moves the file the Head
6. `git push origin master`
  - push: moves the file to the actual remote repository (on GitHub)

Boom, there's your basic workflow.

If you have already cloned the repo but run `git status` and see people have added their own files run `git pull` to pull down the latest and greatest.

