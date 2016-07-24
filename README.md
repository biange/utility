# utility

1. Set up Vundle: </br>
$ git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

2. Install Plugin "YouCompleteMe": </br>
$ git clone https://github.com/Valloric/YouCompleteMe ~/.vim/bundle/YouCompleteMe </br>
$ cd ~/.vim/bundle/YouCompleteMe </br>
$ ./install.py --clang-completer </br>
For more information, please visit http://www.codes51.com/article/detail_121539.html.

3. Install Plugins: </br>
Launch vim and run :PluginInstall

4. File Descriptions: </br>
	- Makefile
	- .vimrc contains optional runtime configuration settings to initialize Vim when it starts.
	- All \*.vim files in the ftplugin directory are configuration files for the corresponding programming languages; </br>
		Now they support C/C++, Java, Shell, python, MATLAB, R, LaTeX and Text file.
	- All \*.tpl files in the template directory are template files for the corresponding programming languges. They will be loaded whenever a new file is created.
	- install.sh is the shell script that installs necessary packages after installing the OS.
