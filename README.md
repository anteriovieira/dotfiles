# Dotfiles

Unix dotfiles

## How to install

```bash
$ bash -c "$(curl -fsSL raw.github.com/anteriovieira/dotfiles/master/bin/dotfiles)"
```

## How to update

You should run the update when:

- You make a change to ~/.dotfiles/git/gitconfig (the only file that is copied rather than symlinked).
- You want to pull changes from the remote repository.
- You want to update Homebrew formulae and Node packages.

Run the dotfiles command:

```bash
$ dotfiles
```