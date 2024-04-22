# azimuth-im
Files and notes for configuring my Linux workstation on azimuth.

## bashrc

Change all instances of `\w` to `\W` in lines which set `PS1` in `~/.bashrc` to
display only the cwd in the bash prompt.

## Installs

### Singularity

Follow the steps here to install a recent version of singularity and its
prerequisites: https://singularity-tutorial.github.io/01-installation/

**NOTE:** add `export PATH=/usr/local/go/bin:$PATH` to `~/.bashrc` _before_
installing singularity to ensure `go` is in PATH.
