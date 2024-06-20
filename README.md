# This repository has been migrated to the self-hosted ari-web Forgejo instance: <https://git.ari.lt/ari/better-bash-baz-plugin>
# Baz plugin: better-bash-baz-plugin

> Baz plugin for making your bash better

# Installation

- Using [baz plugin manager](https://ari-web.xyz/gh/baz):

```bash
$ baz install git 'https://ari-web.xyz/gh/better-bash-baz-plugin'
```

# What does it do

- Enables FZF support
- Enables programmable completion
- Enables TabTab
- Disables annoying shortcuts like `^S`
- Enables `vi` mode
- Enables `autocd` (type directory name to `cd` into it)
- Enables more and extended globbing
- Sets `ENV` to `~/.profile` for `/bin/sh`
- Sets function nesting to `100` so you don't fork yourself
  by accident
- Sets histories to go to `~/.cache`
- Makes bash not store duplicate history entries
- Makes tar `xz` compression best
- Makes FZF better
- Enables a bunch of usability flags for `less`
- Add local `man` pages to `MANPATH`
- Move `.Xauthority` file to a more clean directory
- Move `GTK3` config to `~/.config/gtk-2.0`
- Fixes gpg TTY for signing
- Sets the `JOBS` environment variable for building
- Sets the  visual to your editor
