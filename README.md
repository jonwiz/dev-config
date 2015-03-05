# Devironment

Various Config files for development machine environment setup

Each time I setup a development environment on a new machine - I must hunt down all my
necessary tools, re-config my Vim editor and other software. :(

To save this hassel I'm running this Git Repo to make it easy to deploy new machines
with the tools and configs to make my devironment nice and comfyyy

Git for much win =)

* Download Ruby and Ruby DevKit Mingw64 (http://rubyinstaller.org/downloads/)
* Install Ruby
* Extract Devkit into C:\Ruby{version}\devkit
* Create a desktop shortcut to C:\Ruby{version}\devkit\msys.bat
* Install Git: (http://msysgit.github.io/)
* Install NodeJS: (http://nodejs.org/download/)
* Install awesome npm packages globally using msys.bat console:
```
npm install -g yo grunt bower jslint jshint
```
* Install GVim Editor: (http://www.vim.org/download.php#pc)
* Put vim/_vimrc file into C:\Program Files\Vim\
* Put vimfiles directory contents in C:\Program Files\Vim\vimfiles\
* Install Filezilla FTP Client: (https://filezilla-project.org/download.php?type=client)
* Install WampServer for local Apache/PHP/MySQL for Windows: (http://www.wampserver.com/en/)
