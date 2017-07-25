# .vim
This is my .vimrc file

My .vimrc file is geared toward python development and I have extracted parts of this vimrc file from other developers that are vim purists.  I will likely be making changes to this configuration over time as I figure out what makes best sense for me, but I wanted to store these files so I can pull them down to all of my systems.

##One note:
This puts the .vimrc file in the .vim/ directory rather than at the root directory.  That way it can be tracked within the .vim folder.  So, make sure you do not have a duplicate .vimrc file in the home directory if you want this to be your primary file.  Also, add a soft link to this .vimrc file:
```
rm ~/.vimrc
ln -s ~/.vim/.vimrc ~/.vimrc
```

##bash_profile
This file assumes that you have python 3.5, virtualenv, and virtualenvwrapper installed.  If you do not have these installed, you will need to comment out the lines referring to these dependencies or change them accordingly.
