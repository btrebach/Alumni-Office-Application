Alumni Office Application
=======
This is the repository we will be using for the moment

[Link to handy git guide](http://rogerdudler.github.io/git-guide/)

Everybody should run through the following for some quick 'n dirty git action

*** Adding first steps ***
1. Create your own git repository
  - `cd <location>` - go to your own project folder destination on your computer
  - `git init` - this creates the git repository
2. Create remote "origin" - origin is the name of the remote
  - `git add remote origin git@github.com:btrebach/Alumni-Office-Application.git`
3. Pull from master branch
  - `git pull origin master`

*** Then, do these steps ***
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

If you have already cloned the repo but run `git status` and see people have added their own files run `git pull origin master` to pull down the latest and greatest.

