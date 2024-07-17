# STM
This provides a jitx definition of the STM32H723VGT6 microcontroller.

Right now, it depends on the `tristan/qfp` branch of jsl -- running `main.stanza` will require modifying the `slm.toml` file to point to your local copy of `jsl` at the specified branch.

TODOs:
* remove `main.stanza`
* publish an initial version (there are no tags on the git repo right now)
* double-check decoupling caps
* add pin models if needed
