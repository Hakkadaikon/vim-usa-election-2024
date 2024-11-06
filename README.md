# vim-usa-election-2024

Indicate USA election 2024 in Vim

![vim-usa-election-2024](https://raw.githubusercontent.com/mattn/vim-usa_election_2024/main/misc/screenshot.png)

## Usage

Set `usa_election_2024#status()` into you `statusline` like below.

```vim
set statusline=%<%f\ %h%m%r%=%-14.(%l,%c%V%)\[%{usa_election_2024#status()}\]\ %P
```

For lightline

```vim
let g:lightline = {
\   ...
\   'component_function': {
\     'usa_election_2024': 'usa_election_2024#status',
\   },
\ }
```

## License

MIT

## Author

Yasuhiro Matsumoto (a.k.a. mattn)
