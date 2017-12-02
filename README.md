First install vim-plug in .vim/autoload, open .vimrc and run :PlugInstall


### Configure Rust support

	rustup default stable
	rustup component add rust-src


### Configure YouCompleteMe

	./install.py --clang-completer --rust-completer --build-dir ~/ycm_build/
