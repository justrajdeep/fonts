If it's the first time you check-out a repo you need to use --init first:

    git submodule update --init --recursive

# fonts
my ttf fonts

copy the fonts to `~/.fonts` dir (if dir is not there create one)

    $ cd ~/.fonts
    $ mkfontscale
    $ mkfontdir
    $ ttmkfdir -o fonts.dir
    $ fc-cache -f -v ~/.fonts
    $ fc-cache -f -v
    $ fc-match NonExistingFont   
    
You can confirm that the fonts are installed with the following command:
   
     $ fc-list | grep "Hack"



PS: The nerd-fonts submodule is really big

# License

GPLv2+, just like Mercurial.
