This is a plugin for vim that allows you to easily add imports within a groovy, grails or java project.

INSTALLATION                                           

Vundle (http://github.com/gmarik/vundle)
include the following line in your .vimrc
    Bundle 'sjurgemeyer/vim-grails-import'

Then, run 
    :BundleInstall


Pathogen (https://github.com/tpope/vim-pathogen) 
clone the plugin's git repository
    git clone git://github.com/sjurgemeyer/vim-grails-import.vim.git ~/.vim/bundle/vim-grails-import
If your vim configuration is under git version control, you could also set up
the repository as a submodule, which would allow you to update more easily.
The command is (provided you're in ~/.vim):
    git submodule add git://github.com/sjurgemeyer/grails-import.vim.git bundle/grails-import

You can also just copy the files the old fashioned way, but I don't condone that type of behavior


Please see readme.txt for additional details on usage and configuration.
