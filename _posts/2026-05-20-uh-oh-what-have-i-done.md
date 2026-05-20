---
title: "Uh oh... what have I done."
last_modified_at: 
categories:
  - Blog
tags:
  - personal progress
  - rant
---

Not only have I decided to just do more things with my little "coding" project as of late I have even gone as far as to source control my scripts at work. I have been wanting to have a way to work on larger scripts with the ability to keep version changes tracked. The obvious solution is [Git](https://git-scm.com/), and typically I would just go about using the popular [GitHub](https://github.com/). But with the recent [repositories compromised via employee device](https://cybersecuritynews.com/github-data-breach/) it started to get me wondering if I was going to be able to self-host without standing up a ton of infrastructure to support it. That's where [Gitea](https://about.gitea.com/) comes in, it's very lightweight, but you can install locally and run it as a [Windows Service](https://docs.gitea.com/installation/windows-service)!

Setup of a Gitea local server was very easy as all you had to do was download the installer and run it. I chose to go the route of using SQLite3 for the database and after not even a minute of configuration the server was stood up. I was then able to get the Windows Service setup to run it at the start of my computer. I created a local repository with nothing more then the README and a license to start. I use [Visual Studio Code](https://code.visualstudio.com/download) as my IDE of choice, even with a local instance I was able to clone the newly created repository just as I would have expected to be able to do with a remote repository.

Having source control my own scripts at work on a small self-hosted footprint has been a huge help to cut down on the duplications of scripts with the same name and v1, v2, etc on the file name. Not only was it a fun exercise but it's getting me more understanding of the basics of Git.