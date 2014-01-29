Alumni Office Application
=======
This is the repository we will be using for the moment

[Link to handy git guide](http://rogerdudler.github.io/git-guide/)

Everybody should run through the following for some quick 'n dirty git action

1. Create your local git repository
  - `cd <location>` - go to your own project folder destination on your computer
  - `git init` - this creates the git repository
2. Create remote "origin" - origin is the name of the remote
  - `git remote add origin git@github.com:btrebach/Alumni-Office-Application.git`
3. Pull from master branch
  - `git pull origin master`
4. Clone the repository
  - `git clone git@github.com:btrebach/Alumni-Office-Application.git`
5. Create the file FirstnameLastname.txt
  - `touch FirstnameLastname.txt`
6. Add files to index
  - `git add FirstnameLastname.txt`
7. Moves the file to the Head
  - `git commit -m 'FirstnameLastname initial commit'`
8. `git status` --> should show the file you just created
  - This shows the difference between the Working Directory (your computer) and the Index (staging area)
9. Push the file to the actual remote repository (on GitHub)
  - `git push origin master`

Boom, there's your basic workflow.

If you have already cloned the repo but run `git status` and see people have added their own files run `git pull origin master` to pull down the latest and greatest.

