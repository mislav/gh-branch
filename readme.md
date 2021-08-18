# `gh branch` GitHub CLI extension

Installation:
```
gh extensions install mislav/gh-branch
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
