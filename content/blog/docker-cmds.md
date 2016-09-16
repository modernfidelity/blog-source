+++
author = "Rushton"
categories = ["Docker"]
date = "2016-09-16"
description = ""
featuredalt = ""
featuredpath = "date"
linktitle = ""
title = "Useful Docker Commands"
type = "post"
+++

Some other useful Docker commands to stop / remove all of Docker containers:

    docker stop $(docker ps -a -q)
    docker rm $(docker ps -a -q)
