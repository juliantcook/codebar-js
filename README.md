# Code bar initial JavaScript project guide / starting point

## How to's

### Initialise your own Node project

In a terminal

```bash
# create the directory
mkdir codebar-js
# change to the directory
cd codebar-js
# initialise package.json file (a file to describe your npm project)
npm init
# install a library to serve files locally (--save will add the library to package.json after it is downloaded)
npm install http-server --save
```

## Initialise git

Initialise a git repository so we can have a history of our file changes

```bash
# initialises the git repository
git init
# create a .gitignore file to tell git which files to ignore. Add 'node_modules' to that file. Can be done in any text editor or using the following command
echo 'node_modules' > .gitignore
# add the rest of the files to be tracked by git (the dot means everything in the folder)
git add .
# commit the files along with a message
git commit -m 'first commit'
```

## External tutorials

- git - the simple guide - http://rogerdudler.github.io/git-guide/

## TODOs

- 

