# CSScomb plugin for Vim

## About
Plugin based on CSScomb algorithm.

The algorithm of CSScomb simulates web-technologists actions upon working with CSS-code to the limit. Usually to re-order code you move lines over each other considering comments in the code, multilines records of property values, hacks and everything that could be found in the real file. CSScomb reproduces these actions for you. This means that the parser "thinks" as a person editing the text, not as a blind robot parsing CSS.

For more info, online demo and tests see [csscomb.com](http://csscomb.com/)


## The Requirements

https://github.com/csscomb/csscomb.js

## Installation

### With Pathogen

```
cd ~/.vim/bundle
git clone git://github.com/batsuev/csscomb-vim.git
```

### With Vundle
Add this to .vimrc:
```
Bundle 'git://github.com/batsuev/csscomb-vim.git'
```

### Manual without plugins manager
```
git clone https://github.com/batsuev/csscomb-vim.git csscomb
cp -r csscomb/plugin/* ~/.vim/plugin/
```

## Usage
Vim command:
```
:CSScomb
```
