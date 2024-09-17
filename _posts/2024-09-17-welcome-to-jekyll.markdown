---
layout: post
title:  "Figuring This Out"
date:   2024-09-17 15:10:05 -0400
categories: 
---
Just a brief list of stuff that I did in order to get this up and running, eventually I'll replace this with something a little bit more substantial:

Switched to my GitHub (not github with no capitals, not sure what's the deal with that) folder, in which I created a folder called DigitalHist. _Tip: cd command allows you to change directory to whatever folder you want to work in.
Fixed site not running by changing port from 4000 to 4001 in config, can now update using command 
```
bundle exec jekyll serve --livereload --port 4001
```

Now I can access my updated site online by going to localhost:4001/DigitalHist/ (had to fix to put a space in the port number and the :

