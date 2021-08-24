# `gh branch` GitHub CLI extension

Installation:
```
gh extension install mislav/gh-branch
```

This extension depends on [fzf](https://github.com/junegunn/fzf#readme) as a fuzzy finder. To install using Homebrew:
```
brew install fzf
```

Usage:
```
gh branch
```

Displays an interactive branch switcher that lists local branches in relation
to the pull requests in the repository. The selected branch is checked out.

<!-- You can also select multiple branches with Tab and press Ctrl-D to delete them. -->
