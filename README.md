# junction-zero/brand

The one mark both Junction Zero surfaces carry.

`mark.svg` is authored here and nowhere else. `jzero.fun` and `jzero.run`
consume it as a git submodule at `vendor/brand/` and copy it into their docroot
at build time. Neither redraws it; `jzero.run` only ever recolours it via
`currentColor`.

Do not draw a second mark. If this file and a copy in a surface repo disagree,
this file wins and the copy is the defect.
