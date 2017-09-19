set nocompatible              " be iMproved, required
filetype off                  " required

" set the runtime path to include Vundle and initialize
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()
" Plugins
Plugin 'VundleVim/Vundle.vim'
Plugin 'tpope/vim-surround'
Plugin 'kristijanhusak/vim-hybrid-material'
Plugin 'farmergreg/vim-lastplace'
Plugin 'tomtom/tcomment_vim'
Plugin 'itchyny/lightline.vim'
Plugin 'sheerun/vim-polyglot'
call vundle#end()            " required
filetype plugin indent on    " required
" Brief help
" :PluginList       - lists configured plugins
" :PluginInstall    - installs plugins; append `!` to update or just :PluginUpdate
" :PluginSearch foo - searches for foo; append `!` to refresh local cache
" :PluginClean      - confirms removal of unused plugins; append `!` to auto-approve removal
"
" see :h vundle for more details or wiki for FAQ
" Put your non-Plugin stuff after this line
"

" Lightline
let g:lightline = { 'colorscheme': 'wombat', }               "vim-lightline
set laststatus=2                                                "vim-lightline
set noshowmode                                                  "vim-lightline
" old status line stuff
" set statusline=%F%m%r%h%w\ [FORMAT=%{&ff}]\ [TYPE=%Y]\ [POS=%l,%v][%p%%]\ %{strftime(\"%d/%m/%y\ -\ %H:%M\")}
" :set laststatus=2
" /Lightline

" Colorscheme
:set background=dark
:colorscheme hybrid_material
" /Colorscheme

:set clipboard=unnamed
:set nowrap
:set directory=/tmp
:noh
:set number
:set tabstop=2
:set shiftwidth=2
:set expandtab
:syntax on
:set showcmd
:set cmdheight=1
:set wildmenu
" make backspaces delete sensibly
:set backspace=indent,eol,start

" Map <// to close tag
:iabbrev <// </<C-X><C-O>

" Keys for window movement
" Use Ctrl+[hjkl] to move in the desired direction
map <C-J> <C-W>j
map <C-K> <C-W>k
map <C-H> <C-W>h
map <C-L> <C-W>l
