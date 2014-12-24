Ruby on Rails Setup for Development
===================================

Ubuntu 14.04 LTS or 14.10
-------------------------

### Install Latest Version of Git 2.2.0
In Terminal, type the following:

```
sudo add-apt-repository ppa:git-core/ppa
sudo apt-get update
sudo apt-get install git
git config --global user.name "Full Name"
git config --global user.email "me@me.com"
```

https://github.com/yui/yui3/wiki/Set-Up-Your-Git-Environment

https://help.github.com/articles/generating-ssh-keys/

Windows 7/8/8.1
---------------
### Step 1 - Install Git
Download and Install Git from:
  http://git-scm.com/downloads
- Git Version 1.95 can be downloaded directly: https://github.com/msysgit/msysgit/releases/download/Git-1.9.5-preview20141217/Git-1.9.5-preview20141217.exe
- Install to C:\Git
- Select 'Use Git from the Windows Command Prompt'

### Step 2 - Install Ruby and DevKit
Download and Install Ruby from:
  http://rubyinstaller.org/downloads/
- Ruby Version 2.1.5 x64 can be downloaded directly: http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.1.5-x64.exe?direct 
- Install it to `C:\Ruby`
- Select 'Add Ruby executables to your PATH' and 'Associate .rb and .rw files with this Ruby installation'

Download and Install DevKit from:
  http://rubyinstaller.org/downloads/
- Direct Link: http://cdn.rubyinstaller.org/archives/devkits/DevKit-mingw64-64-4.7.2-20130224-1432-sfx.exe
- Extract files to 'C:\Ruby\DevKit'
- In Command Prompt type:
```
$ C:\Ruby\DevKit\dk.rb init
$ C:\Ruby\DevKit\dk.rb install
```

### Step 3 - Install Rails

### Step 4 - Install Other Software

Learning Guides
---------------
- Ruby
  - Learn to Program, by Chris Pine - https://pine.fm/LearnToProgram/
  - Learn Ruby the Hard Way, 3rd Edition - http://learnrubythehardway.org/book/
- Rails 
  - XYZPub - http://www.xyzpub.com/
  - Ruby on Rails Guides - http://edgeguides.rubyonrails.org/index.html
  - Ruby on Rails Tutorial - Michael Hartl - https://www.railstutorial.org/book
- Markdown
  - Markdown Basics - https://help.github.com/articles/markdown-basics/
  - Markdown Cheatsheet - https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
  - GitHub Flavored Markdown - https://help.github.com/articles/github-flavored-markdown/
- Git
  - git - the simple guide - http://rogerdudler.github.io/git-guide/
- HTML & CSS
  - HTML and CSS: Design and Build Websites - by Jon Duckett - $17.39 - http://www.amazon.com/dp/1118008189
  - Dash - https://dash.generalassemb.ly/
  - Learn to Code HTML & CSS - http://learn.shayhowe.com/html-css/
  - Learn CSS Layout - http://learnlayout.com/
  - A Complete Guide to Flexbox | CSS-Tricks - http://css-tricks.com/snippets/css/a-guide-to-flexbox/

Useful Stuff
------------
The best developer tools, now free for students https://github.com/blog/1900-the-best-developer-tools-now-free-for-students

Sources
-------
- Setup Ruby On Rails on Ubuntu 14.10 Utopic Unicorn - https://gorails.com/setup/ubuntu/14.10
- How To Install Ruby on Rails on Ubuntu 12.04 LTS (Precise Pangolin) with RVM - https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-on-ubuntu-12-04-lts-precise-pangolin-with-rvm
- How I TRAINed to learn Rails - Richardson Dackam - https://medium.com/how-i-learned-ruby-rails/how-i-trained-to-learn-rails-e08c94e2a51e
