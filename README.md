<img src="https://i.imgur.com/xAn3dvK.png">

#dev-environment-lab

## OS

darwin21.0

## Shell

/bin/zsh

## zsh location

/bin/zsh

## code alias

/usr/local/bin/code

## GitHub CLI version

gh version 2.4.0 (2021-12-21)
https://github.com/cli/cli/releases/tag/v2.4.0

## npm version

8.1.2

## node version

v16.13.2

## nodemon version


## Heroku version

heroku/7.59.2 darwin-x64 node-v12.21.0

## Git version

git version 2.34.1

## Git Default Branch

main

## Git Merge Behavior

false

## Global Git Ignore

/Users/test/.gitignore_global

## Contents of ~/.gitignore_global

# This is a list of rules for ignoring files in every Git repository on your 
# computer. See https://help.github.com/articles/ignoring-files

# GitHub maintains a repository of items that can generally be gitignored 
# globally safely at: https://github.com/github/gitignore/tree/master/Global

# GitHub also maintains a repository of language-specific items that should
# typically be ignored on a per-project basis with a .gitignore in that
# project's root directory. 
# This repository can be found at: https://github.com/github/gitignore

# This file DOES include items that would typically not be gitignored globally
# for simplicity during the course, but this may cause issues as you further
# your education post-SEI. These items are denoted when used here and are kept 
# to a minimum.

###############################################################################
#   The items in this section are generally safe be globally gitignored and   #
#         are very unlikely to cause projects to break if left here.          #
###############################################################################

#================================= Archives ==================================#
#                Unpack these files and commit the raw source.                #
#                git has its own built in compression methods.                #

# Compressed Files #
*.7z
*.jar
*.rar
*.zip
*.gz
*.gzip
*.tgz
*.bzip
*.bzip2
*.bz2
*.xz
*.lzma
*.cab
*.xar

# Packing-only formats #
*.iso
*.tar

# Package management formats #
*.dmg
*.xpi
*.gem
*.egg
*.deb
*.rpm
*.msi
*.msix
*.msm
*.msp
*.txz

#===================== Operating System Generated Files ======================#
#----------------------------------- Linux -----------------------------------#
# Temporary files created as backups by text editors or similar programs #
*~

# Temporary files created if a process is still accessing a deleted file #
.fuse_hidden*
.nfs*

# KDE directory preferences #
.directory

# Linux trash folder which might appear on any partition or disk #
.Trash-*

#----------------------------------- macOS -----------------------------------#
# General #
.DS_Store
.DS_Store?
.AppleDouble
.LSOverride

# Thumbnails #
._*

# Files that might appear in the root of a volume #
.DocumentRevisions-V100
.fseventsd
.Spotlight-V100
.TemporaryItems
.Trashes
.VolumeIcon.icns
.com.apple.timemachine.donotpresent

# Directories potentially created on remote AFP share #
.AppleDB
.AppleDesktop
Network Trash Folder
Temporary Items
.apdisk

#---------------------------------- Windows ----------------------------------#
# Windows thumbnail cache files #
Thumbs.db
Thumbs.db:encryptable
ehthumbs.db
ehthumbs_vista.db

# Dump file #
*.stackdump

# Folder config file #
[Dd]esktop.ini

# Recycle Bin used on file shares #
$RECYCLE.BIN/

# Windows shortcuts #
*.lnk

#==================================== Tags ===================================#
# Ignore tags created by etags, ctags, gtags (GNU global) and cscope #
tags

#============================ Visual Studio Code =============================#
# .vscode excluding certain .json files #
.vscode/*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json

# Local History for Visual Studio Code #
.history/

###############################################################################
#   The items in this section may not typically be gitignored globally and    #
#               may cause future projects to break if left here.              #
# ** However, if you remove them from here, you MUST add them back to the **  #
#  ** projects they apply to by placing a .gitignore containing the items **  #
#           ** to be gitignored in each project's root directory. **          #
###############################################################################

#=========================== Compiled Source Code ============================#
# Class Files #
*.class

# Dynamic Libraries #
*.so
*.dylib
*.dll

# Executables #
*.com
*.exe
*.out
*.app

# Object Files #
*.slo
*.lo
*.o
*.obj

#================================== Django ===================================#
# Logs #
*.log

# Local django settings #
local_settings.py

# SQL database #
db.sqlite3
db.sqlite3-journal

#============================== Node and Python ==============================#
# Environment variables #
.env

#=================================== Node ====================================#
# Dependencies #
node_modules

#================================== Python ===================================#
# Byte-compiled #
*.py[cd]
__pycache__/
.python-version

#================================== React ====================================#
.eslintcache
