# dotfiles

## Services and corresponding config locations
- nvim: ~/.config/nvim

## Dependencies
### neovim from source (can't use apt-get version, lsp issues)
```
git clone https://github.com/neovim/neovim
cd neovim
sudo apt install make
sudo apt install cmake
make CMAKE_BUILD_TYPE=Release
sudo make install
```
