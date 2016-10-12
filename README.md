
#Config vim to be an IDE
## Steps :
Clone repository
```
git clone https://github.com/se7oluti0n/Vim-config.git
```
Copy .vimrc to home folder
```
cp Vim-config/.vimrc .
```
Install plugins
```
vim +PluginInstall
```
The installing will stop at YouCompleteMe, exit Vim, then
```
cd ~/.vim/bundle/YouCompleteMe
git submodule update --init --recursive
./install.sh
```
Config YouCompleteMe for C/C++
```
:YcmGenerateConfig
```
Then install remains plugins
```
vim +PluginInstall
```
Install exuberant ctags for create tags
```
sudo apt-get install exuberant-ctags
```
Update latest Vim
```
sudo add-apt-repository ppa:pkg-vim/vim-daily
sudo apt-get update && sudo apt-get upgrade
```
