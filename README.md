ctrlp-leader-guide
==============

A Vim plugin for showing all your `<Leader>` mappings with `CtrlP`'s interface.

Installation
------------

Use your favorite method install this plugin, for example using [junegunn/vim-plug](https://github.com/junegunn/vim-plug):

```viml
Plug 'https://codeberg.org/acook/ctrlp-leader-guide.git'
```

Features
--------

* List `<Leader>` mappings defined by the user and the plugins
* By default only mappings defined in `.vimrc` are listed. It honours `$MYVIMRC` variable
* Mappings from all scripts sourced by Vim can be listed if specified by configuration (see Options)
* If the line previous to the mapping is a comment it will be used as the description
* If no comment is available the **rhs** (command) of the mapping is used as description

Screenshots
-----------

![screenshot](https://cloud.githubusercontent.com/assets/4246425/21986374/1fd26d88-dc3a-11e6-8de7-384c4cddc5c1.png)


Options
-------

* `g:fml_all_sources`: if `1` all sources are used, if `0` just `$MYVIMRC` is used. Default `0`

Credit
-------

- Gastón Tonietti (`ktonga`), the original creator of [vim-follow-my-lead](https://github.com/ktonga/vim-follow-my-lead)
- `tracyone` for porting `vim-follow-my-lead` to `CtrlP`
- Mladen Mijatov (`MeanEYE`) for [preserving it](https://github.com/MeanEYE/ctrlp-leader-guide)