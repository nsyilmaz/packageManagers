# Package Managers
## Homebrew
List installed packages
```sh
brew list
```
Information about a package
```sh
brew info certifi
```
Uninstall a package
```sh
brew uninstall semgrep
```
Install a package
```sh
brew install certifi
```
Update homebrew itself
```sh
brew update
```
Upgrade all installed packages
```sh
brew upgrade
```
Upgrade a package
```sh
brew upgrade certifi
```

#####

## Pip
List installed packages
```sh
pip3 list
```
Information about a package
```sh
pip3 show wheel
```
Uninstall a package
```sh
pip3 uninstall setuptools
```
Install a package
```sh
pip3 install setuptools
```
Update homebrew itself
```sh
pip3 install -U pip
```
Upgrade a package
```sh
pip3 install -U wheel
```
#####

## Node - npm - yarn
List installed packages
```sh
npm list
```
```sh
yarn list
```
install from package.json
```sh
npm i
```
```sh
yarn i
```
Uninstall a package
```sh
 npm uninstall jest@29.7.0
```
```sh
yarn remove jest@29.7.0
```
Install a package
```sh
npm install jest@29.7.0
```
```sh
yarn add jest@29.7.0
```
Update npm itself
```sh
npm install -g npm@latest
```
```sh
npm install -g yarn@latest
```
Global install
```sh
npm install -g npm@9 
```
```sh
npm install -g yarn@9
```


#####
## Cut/copy/paste/undo/redo
* Cut/Delete char - `x`
* Cut/Delete line - `dd`
* Copy line - `yy`
* Paste - `p`
* Undo - `u`
* Redo - `CTRL-R`
* Repeat last command - `.`
#####

## Navigate in file
* Go to first line - `:1`
* Go to n'th line - `:n`
* Go to last line - `:$`
* Go to beginning of line  - `^`
* Go to end of line  - `$`
#####

## Quickly indent/outdent multiple lines
* Enter VISUAL LINE mode - `SHIFT+V`
* Use the `SHIFT` and `arrow keys` or `j` and `k` to select the lines you want to indent.
* Hit the `>` character (`SHIFT+.`) to indent.
* Likewise, hit the `<` character (`SHIFT+,`) to outdent the selected lines.
* Then, you can repeat the indent using the `.` (repeat key) key. 
#####

## Quickly insert on multiple lines
* Put `#` character at the beginning of lines between 1-13
```
:1,13s/^/#/g
```
OR

* Enter VISUAL BLOCK mode - `CTRL+V`
* Use the `SHIFT` and `arrow keys` or `j` and `k` to select the lines you want to insert string.
* Hit the `SHIFT+i` and type the text you want to insert.
* Then, hit `ESC`.
#####





## Code completion
* Type something and then press `CTRL+P`
#####

## ~/.vimrc
* Syntax coloring and font settings
```vim
:syn on
:set guifont=Menlo\ Regular:h16
:colorscheme OceanicNext
if has("gui_macvim")
    let macvim_hig_shift_movement = 1
endif
```

* Indentetion and tab settings
```vim
set expandtab       "Use softtabstop spaces instead of tab characters for indentation
set shiftwidth=4    "Indent by 4 spaces when using >>, <<, == etc.
set softtabstop=4   "Indent by 4 spaces when pressing <TAB>
set autoindent      "Keep indentation from previous line
set smartindent     "Automatically inserts indentation in some cases
set cindent         "Like smartindent, but stricter and more customisable
autocmd FileType make set noexpandtab shiftwidth=8 softtabstop=0
```
#####
