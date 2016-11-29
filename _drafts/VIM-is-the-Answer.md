---
title: Vim Is The Answer
date: 2016-11-29 23:25:33.876000000 Z
---

## VIM is the Answer

### Why Sublime when VIM is everywere!

I avoided VIM, I have to admit that. I had to accept that fact before I could finally embrace and accept what was an easier learning curve than I originally expected to get moving with VIM. But why VIM and not the awesome Sublime or WriteMonkey (also awesome)? And the answer is very simple: VIM is everywhere. And it is almost everywhere by default now. You know it's 2014 right? 

#### On Windows? 
Run a single install of VIM from the Desktop (gVim), Command Line (vim), or PowerShell (vim). The plugins and changes you make to your `.vimrc` or on a Windows machine the `_vimrc` file will be used on any instance of Vim that you fire up. It's awesome. It's free (but please donate). And it is still being updated, tweaked, and expanded by a lot of people who are writing plugins. 

Before I finally gave up and surrendered to the Vim I was trying out or using the following for various text editing tasks.

* SublimeText (Win,Unix,Mac)
* Notepad or Notepad++ or Notepad2 (Win)
* MarkdownPad or WriteMonkey (Win)

But with few exceptions and a slight learning curve, anything you can do in one of the above editors you can do with Vim or with Vim and a Plugin. You learn ONE set of keyboard shortcuts, ONE methodology, and have to keep up with ONE config file across any platform you need to use. Store your config on github.com as a public or even private repo and you can pull it down within a minute and have everything just the way you like it. Did you fire up a new $5 VPS from DigitalOcean? `git clone https://github.com/briankb/_vimrc ~/vim` and boom!!! there you go.


#### On Linux/Mac

Here is a list of the major operating systems that include some version of VIM (Vi IMproved). 

Awesome Editors (you don't really need)


### Getting Setup on Windows OS
go to [http://www.vim.org](www.vim.org) and download the install for Windows. Do NOT however install it to the default of C:\Program Files, unless you want to deal with endless popups from windows security. It will work perfectly fine and still be safe in your User profile folder. On Windows 7 or 8 that is `C:\Users\(YourName)` or you can pop to a command window `Win+R then %USERPROFILE%` to see which user and user folder you are working in currently. The rest of this brief tutorial will assume you are installing it in your user profile folder.

### Getting Setup on Linux/Mac
nothing to do here, it's probably already there... just type `vim --version` on the command line once you are logged into a session. 



### Must Have Plugins

* [Vundle](https://github.com/gmarik/Vundle.vim) - plugin manager ([github repo](https://github.com/gmarik/Vundle.vim.git))
* [Fugitive](https://github.com/tpope/vim-fugitive) - git repo wrapper/manager ([github repo](https://github.com/tpope/vim-fugitive.git))
* [NERDTree](https://github.com/scrooloose/nerdtree) - file exployer sidebar ([github repo](https://github.com/scrooloose/nerdtree.git))
* [EasyMotion](https://github.com/Lokaltog/vim-easymotion) - motions on steroids! ([github repo](https://github.com/Lokaltog/vim-easymotion.git))
* [SparkUp](https://github.com/rstacruz/sparkup#examples) - wright HTML code faster ([github repo](https://github.com/rstacruz/sparkup.git))
* ~~[L9](https://github.com/vim-scripts/L9) -  script library that provide some utility functions and commands for programming Vim ([github repo](https://github.com/vim-scripts/L9.git))~~
* [FuzzyFinder](http://www.vim.org/scripts/script.php?script_id=1984) - pattern exployer ([bitbucket repo](https://bitbucket.org/ns9tks/vim-fuzzyfinder))
* ~~[Command-T](http://www.vim.org/scripts/script.php?script_id=3025) - extremely fast file openiner, inspired by TextMate ([tutorials](https://wincent.com/products/command-t)) ([wincet git repo](git://git.wincent.com/command-t.git))~~ *requires ruby