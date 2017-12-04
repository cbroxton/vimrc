## Install

1) Install vim-plug in ~/.config/nvim/autoload
2) Copy init.vim to ~/.config/nvim/
3) Run :PlugInstall


## Configure Rust support

	rustup default stable
	rustup component add rust-src
	cargo install racer
