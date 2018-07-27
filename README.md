# Twig.vim
Twig syntax highlighting, indentation, neocomplete and UltiSnips snippets in
Vim

## Installation
To install twig.vim and other Vim plug-ins it is recommended to use one of the
popular package managers for Vim, rather than installing by drag and drop all
required files into your .vim folder.

### Neobundle (recommended)
1. Setup the [neobundle](https://github.com/Shougo/neobundle.vim) package
	 manager
2. Set the bundles for [twig.vim](https://github.com/nelsyeung/twig.vim)

    ```vim
    NeoBundle 'nelsyeung/twig.vim'
    ```

3. Open up Vim and start installation with `:NeoBundleInstall`

### Vundle
1. Setup the [vundle](https://github.com/gmarik/vundle) package manager
2. Set the bundles for [twig.vim](https://github.com/nelsyeung/twig.vim)

    ```vim
    Plugin 'nelsyeung/twig.vim'
    ```

3. Open up Vim and start installation with `:PluginInstall`

### Manual (not recommended)
1. Download the [twig.vim](https://github.com/nelsyeung/twig.vim) files
2. Put files in your Vim directory (usually `~/.vim/` or
	 `%PROGRAMFILES%/Vim/vimfiles` on Windows)

## Snippets
This package does not include the old snipMate snippets in favour of
[Neosnippet](https://github.com/Shougo/neosnippet.vim). Follow the instructions
on their page to get snippets working. Although a
[neosnippet-snippets](https://github.com/Shougo/neosnippet-snippets/pull/113)
have the snippets from this package, it might not be the latest version. To
have the latest snippets working, you can add to your .vimrc

```vim
let g:neosnippet#snippets_directory='~/.vim/bundle/twig.vim/neosnippets'
```

## Todo
- Better filetype detection. Detect html.twig, js.twig differently. This will
	need to change both ftdetect and indent files.
- More useful snippets.
