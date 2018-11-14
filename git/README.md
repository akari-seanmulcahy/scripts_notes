# hello-world

Initial play around with GIT & GITHUB. It's slightly different to CVS!

## GIT SSH Key Setup:

###### Add your GIT account to the organisation you are part of
E.g.: Git account(seaniemul) needs to be added to the Sky-uk organisation in git-SAML and 2 factor authentication

###### Setup ssh key so you don't need to log on each time:
https://help.github.com/articles/connecting-to-github-with-ssh/
###### Once setup and the ssh key has been added to your GIT hub account then the final step is to authenticate this against your ogranisation. 
###### Click on the SSO link on your SSH Key settings page: 
https://github.com/settings/keys

###### Now you can clone a repo
`git clone git@github.com:sky-uk/csc-map-adi-ingest.git`

Sky repos require use of the ssh key and passphrase where as personal accounts can use the https link:
`git clone https://github.com/seaniemul/hello-world.git`

Alternatively you can uss ssh keys here too:
`git clone git@github.com:seaniemul/hello-world.git`

## GIT Notes:
`git log` # to see what happened.

to see what you are in the middle of doing, use one of:
* `git diff`
* `git status`

###### commit some code
`git commit -m "Message while you are commiting code" <file>`

###### push code locally to the shared repo
`git push`

###### Create a new branch
`git checkout -b B_comment_changes`
Switched to a new branch 'B_comment_changes'

find out what branch are you on
`git status`
Swap to master and pull to get latest changes
```
git checkout master
git pull
```

###### Create a new repo.
1. Click on New Repository button
If you have a folder already, in that folder type: 
```
git remote add origin git@github.com:seaniemul/scripts_notes.git
git push -u origin master
```

###### Markup code for README pages like this
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet 
