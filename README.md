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


PS: The nerd-fonts submodule is really big

# License

GPLv2+, just like Mercurial.
