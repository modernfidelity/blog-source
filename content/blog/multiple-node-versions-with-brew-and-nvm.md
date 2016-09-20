+++
author = "Rushton"
categories = ["Javascript", "Node"]
date = "2016-09-20T11:28:28+01:00"
description = ""
featured = ""
featuredalt = ""
featuredpath = ""
linktitle = ""
title = "multiple node versions with brew and nvm"
type = "post"

+++



# Install multiple node versions with brew and nvm

Make sure you have [Homebrew](http://brew.sh/) installed and then run the following : 

    brew update
    brew install nvm
    mkdir ~/.nvm
    
    
Then in particular shell of choice i.e. .bash_profile add : 
    
    export NVM_DIR="$HOME/.nvm"
    source $(brew --prefix nvm)/nvm.sh
    
    
Update your current session to run the changes : 
     
     source ~/.bash_profile 
     
Now, you can install node :
     
     nvm install 4.5.0
     nvm install 6.6.0
     
Switch of node version with 

    nvm use 6.6.0
     
To have a node activated by default (not to have to nvm use on each new shell), run this (stable being the id of the version):

    nvm alias default 6.6.0
    
Success - you can now run multiple versions of node ;)  