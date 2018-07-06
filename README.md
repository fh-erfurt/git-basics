# git-basics

## Level 1: Basic Commands

Q1. Figure out how to call the help section of the git cli-tool locally.

`$ git help`

Q2. Where do you find help about the config?

`$ git help config`
`$ git config --help`

Q3. Create a config for your username, your mail address and enable the terminal colors!

`$ git config --global user.name "Benjamin Nothdurft"`  
`$ git config --global user.email benjamin.nothdurft@company.com`  
`$ git config --global color.ui true`

Q4. Create a local directory named "store" and change into it. Then initialize a new git repository and check the status.

`$ mkdir store`  
`$ cd store`  
`$ git init`  
`$ git status`

Q5. Create a bunch of `*.txt` files with the touch command into the directory and figure out how to add them with the following strategies to the index. You can use the status command to check if it worked.

`$ touch a.txt b.txt c.txt d.txt a.doc b.doc c.doc` etc.

a) as individual file

`$ git add README.txt`

b) as a list of files

`$ git add <list of files>`

c) all new and unmodified files

`$ git add --all`

d) all files with a certain pattern of the current dir

`$ git add *.txt`

e) all txt files in a subdirectory called `docs`

`$ git add docs/*.txt`

f) all files of the directory `docs

`$ git add docs/`

e) all files in the whole git project with a certain pattern

`$ git add "*.txt"`

Q6. Learn more about the commit command

a) Commit with a message

`$ git commit -m "Create a README"`

b) Commit with a message and include untracked files

`$ git commit -a -m "message."`  
`$ git commit -am "message."`

c) Use the log command to ckeck what worked

`$ git log`
