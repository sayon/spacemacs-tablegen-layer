# spacemacs-tablegen-layer
A layer that packs a modified version of tablegen-mode from llvm


This is a separate project for now because for `spacemacs` community it might be better to
first publish `tablegen-mode` as a package on ELPA and then wrap it (and
possibly also MLIR related modes) in a layer.

# Installation

1. Copy `tablegen` to `~/.emacs.d/layers/+lang/` directory.
2. Add `tablegen` to `dotspacemacs-configuration-layers` in `~/.spacemacs`.
