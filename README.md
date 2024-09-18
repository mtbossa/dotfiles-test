# dotfiles - Manual
My dotfiles bare repo.

* Based in the [Dotfiles: Best Way to Store in a Bare Git Repository](https://www.atlassian.com/git/tutorials/dotfiles) tutorial.

## How to run using chezmoi
```
export GITHUB_USERNAME=logandonley
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME
```
