# Wikitext syntax highlight file for GNU nano text editor
Quick and dirty nanorc file for [Wikitext](https://meta.wikimedia.org/wiki/Community_Tech/Wikitext_editor_syntax_highlighting) support on [GNU nano text editor](https://www.nano-editor.org/). 
## Installation
1. Copy the file 
2. Put it in the `~/.nano/` directory
3. Add it to nano’s included files by adding `include ~/.nano/cooklang.nanorc` into `~/.nanorc` (User specific) or `/etc/nanorc` (System wide).
## Note
This file aims to reproduce the "official" built-in wiki editor’s syntax highlight.
Although [officially documented by nanorc](https://www.nano-editor.org/dist/latest/nanorc.5.html) my [terminal](https://gitlab.xfce.org/apps/xfce4-terminal) (xfce4-terminal 0.8.9.1) limitations seem to prevent the use of colours and emphasis. Those parts are commented out, so that you can uncomment them and test if your terminal support them.
