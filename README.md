# Wikitext syntax highlight file for GNU nano text editor
Quick and dirty nanorc file for [Wikitext](https://www.mediawiki.org/wiki/Help:Formatting) support on [GNU nano text editor](https://www.nano-editor.org/). 
## Installation
1. Copy the file 
2. Put it in the `~/.nano/` directory
3. Add it to nano’s included files by adding `include ~/.nano/cooklang.nanorc` into `~/.nanorc` (User specific) or `/etc/nanorc` (System wide).
## Note
This file aims to reproduce the "official" built-in wiki editor’s syntax highlight.
Although [officially documented by nanorc](https://www.nano-editor.org/dist/latest/nanorc.5.html) my [terminal](https://gitlab.xfce.org/apps/xfce4-terminal) limitations seem to prevent the use of "grey" for comments. While I could have substitued it for white, I explicitly left it as defaulted so that it would match users’ themes by default while pointing them to the value to modify if necessary.For the same reasons, I left explicit the multiple lists beginnings so that anyone could quickly modify the values for better list differenciation, and I didn’t use the bold and italic arguments.
