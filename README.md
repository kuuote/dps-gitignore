# dps-gignore

Generating gitignore using [gitignore.io](https://www.toptal.com/developers/gitignore)

## Requirements

* [denops.vim](https://github.com/vim-denops/denops.vim)

## Installation

```
Plug 'tamago324/dps-gignore'
```

## Usage


### GignoreSetlines

Insert into current buffer.

```
:GignoreSetlines vim lua
```


### GignoreGenerate


Create a gitignore for the git repository in the current directory (`getcwd()`).

```
:GignoreGenerate vim lua
```


## Configuration

```
" Cache directory for language list
let g:dps_gignore_cache_dir = expand('~/.cache/dps-gignore')
```


## Contributing

* All contributions are welcome.


## License

MIT