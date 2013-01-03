Laptop
======

Laptop is a script to set up a Mac OS X laptop for Rails development.

Requirements
------------

1) Install a C compiler.

Use [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action)
for Lion (OS X 10.7) or Mountain Lion (OS X 10.8).

2) Set zsh as your login shell.

    chsh -s /bin/zsh

Install
-------

Run the script:

    zsh < <(curl -s https://raw.github.com/TheGiftsProject/laptop/master/mac)

What it sets up
---------------

* Oh My ZSH 
* SSH public key for authenticating with Github and Heroku
* Homebrew for managing operating system libraries
* Ack for finding things in files
* ImageMagick for cropping and resizing images
* CTags for indexing files for vim tab completion of methods, classes, variables
* RVM for managing versions of the Ruby programming language
* Ruby stable for writing general-purpose code
* Some Ruby Gems - [Bundler, Foreman, Rails, Thin]
* Heroku Toolbelt for interacting with the Heroku API & Heroku Config plugin for local `ENV` variables
* Nginx for serving http and reverse proxy
* Pow for zero config rack local development
* Powder gem for managing pow
* MySQL for being a database
* NodeJS for hacking on node and for js compilation
* Some .dot-files in your home directory - .rdebugrc, .gemrc, .irbrc
* EyToolBox for easy managment and deployment of projects



Make sure that you set up your self-signed SSL keys for nginx

It should take less than 15 minutes to install (depends on your machine).
