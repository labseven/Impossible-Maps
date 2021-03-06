# Getting set up for the semester 

## Overview 
Even though the majority of the class will be taught in Python, we'll need Here's an overview (not exhaustive) of some additional, foundation things that we'll be using or referring to over the semester:

- **Terminal**: Also known as the command line, or shell, or console. It's an interface in which you can type and execute text based commands. It's just like Finder, but is another (often faster and more direct) way of interacting with the computer. 
- **Git**: an open-source version control system that tracks changes to a file. A tool used with the command line, useful for maintaining and referring to multiple versions of a file.
- **Github:** web hosting service for code. A place where programmers can share/store their projects and code, and interact with the code and projects of other people. 
- **Github Pages:** Public webpages hosted for free through GitHub. GitHub users can create and host both personal websites (one allowed per user) and websites related to specific GitHub projects.
- **Markdown:** a lightweight text format that exports easily to HTML (as well as other formats) and allows us to write using any plain text editor. This document is written in Markdown. 
- **Text Editor:** A program that allows us to create and edit programming language files in plain text. This is the place where we'll be writing most of our code. We'll be using Sublime Text, though you're free to use your own if you already have a favorite. 


This guide assumes that you have a Macbook. Terms in `monospace` are either code or things that you will need to type into the terminal and then press enter. Don't type the `$` that may precede some of these terms.   


## Setting up our computers 

We'll be using the console, or the terminal, a lot this semester, so you'll have many chances to get familiar with it. Don't worry if some of the things that we do in this guide are confusing to you, it'll all make sense in time. 

1. **Install homebrew** </br> [Homebrew](https://brew.sh/) is a package manager for your OSX (the operating system that Macs run), it will help us manage programs on the computer. </br></br> To install, copy and paste this into your terminal window: `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` </br></br>*Note:* if you get an error saying that you don't have permission to install this, you may have to sudo the command. That means typing in the word `sudo` before the command, and pressing return. You'll then be prompted to enter your password; type it in and press return, and be aware that as a security measure nothing may show up in the screen even though you're typing. 

2. **Download Sublime Text** </br> Available [here](https://www.sublimetext.com).

## Setting up Git and Github 
Most of the resources and materials and our class will be available on Github. You won't need Git or a Github account to interface with those materials, but it will make things easier for you, and will be useful when it comes to the blogs. 

### Sign up for Github 

1. Go to [github.com](github.com/) and click the button to join or sign up for the site.
2. You'll have to choose a username, email address, and password. When you get to the next screen, choose the free plan. For now, you can skip the page about tailoring your experience.
3. Follow the instructions to verify your email address: go to your email account and click the link so that it's verified. 


### Download and set up Git 

On a Mac, downloading Git is easy. Just go to your terminal and type `git`. You should be immediately prompted to install. If not, go [here](github.com/) to download.

Once git is installed, we need to execute some one-time commands that will allow you to easily interface with github from the command line. 

NOTE: don't do these if you're on a public computer! Also, note that these values will be stored with Git, so make sure that you're okay with the email address being public. 


`$ git config --global user.name "YOUR_FULL_NAME"`
`$ git config --global user.email "YOUR_EMAIL_ADDRESS"`

See below for an example: </br>
`$ git config --global user.name "John Doe"`
`$ git config --global user.email johndoe@example.com`

Voila! 

## Setting up your blog
### Why Are We Doing This?
For the semester, you're required to have a website or blog where you respond to assignments, post your homework, and document your projects. You have a few options for this: you can either use Github Pages, host a website yourself, or use an existing  content management system (such as Tumblr, Wordpress, etc.)

I am going to be showing you how to use Github Pages, for a number of reasons. First, the structure of updating your github webpage is similar to the process of using git in general. Second, we want to use open-source projects whenever possible. Third, while the process might be confusing now, it's one that you can use whenever you want, so in the future you'll be able to easily host things online. 

In short, I think using Github Pages is empowering. But for newbies, it can also be a little overwhelming, so if you find things too complicated, feel free to use a different platform for your website. 

### How to set up a blog with Github Pages

The instructions on [this page](https://guides.github.com/features/pages/) are super clear. 


## Resources
- For more on git, github, and github pages, see [here](http://jmcglone.com/guides/github-pages/)
- [An introduction to git](https://sklise.com/2012/09/22/introduction-to-git/) (it's old, but very clear)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- More on [Jekyll Now](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/)
