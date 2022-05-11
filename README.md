# [chezmoi](https://www.chezmoi.io/) Dotfiles Management


## Install

* [Install](https://www.chezmoi.io/docs/install/) the `chezmoi` binary
* `chezmoi init https://github.com/bmckenna805/dotfiles.git`
* `chezmoi apply`

## Acknowledge source

I learned how to use chezmoi largely by looking at [https://github.com/speshak/dotfiles](https://github.com/speshak/dotfiles) so full credit where credit is due.  He also explained how his template for environment based variables works.

## In the event of needing a new environment

1. Install chezmoi
1. Init and apply chezmoi
1. Set up your new GPG key
   1. Add key to github profile
   1. Edit .gitconfig and .gnupg/gpg.cong with new key value
   1. Edit related dotfiles and commit to this repo
   1. Edit the `.chezmoi.toml.tmpl` file with the new email and gpg key ID
