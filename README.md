study git usage at http://blog.jobbole.com/25808/

add ssh key refer to http://my.oschina.net/flan/blog/162189

study scala at http://docs.scala-lang.org/tutorials/scala-for-java-programmers.html


setup vim environment for editing scala script
refer tool from https://github.com/scala/scala-dist/tree/master/tool-support/src/vim

copy ftdetect, indent, syntax, plugin these 4 folders to ~/.vim/
and then vim ~/.vimrc contents as following:

set nocompatible 
set backspace=indent,eol,start 
set ts=4 
set keymodel=startsel 
set nu 
set autoindent 
set ruler 
syntax on 
colorscheme torte 
set gfn=Anonymous:h12 
set anti 
