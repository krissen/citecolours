# citecolours

Selective colouring of biblatex citations and bibliography entries.

## Usage

```tex
\usepackage[sources={key1,key2},rgb={12,127,172}]{citecolours}
```

Options: `sources`, `rgb`, `color`, `inlinebold`, `bibbold`, and the
backwards-compatible `bold` alias. Helpers: `\addcolouredsource` and
`\removecolouredsource`.

## Build and test

```sh
make check
make install
```

## Licence

LPPL 1.3c, see `LICENSE`.
