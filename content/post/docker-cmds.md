+++
Categories = ["Development"]
Description = ""
Tags = ["Development", "Docker"]
date = "2016-09-05T08:43:18+01:00"
title = "docker cmds"

+++

Some other useful Docker commands to stop / remove all of Docker containers:

    docker stop $(docker ps -a -q)
    docker rm $(docker ps -a -q)
