# gh-todo

🗓 GitHub CLI extension for manipulating todo's managed by GitHub Issues using `fzf`.

## Requirements

- [junegunn/fzf](https://github.com/junegunn/fzf)
- todo repository `{username}/todo`

## Install

```
gh extension install arrow2nd/gh-todo
```

## Usage

```
# List todo
gh todo

# Add todo
gh todo add stroke a cat

# Show help
gh todo --help
```

### Note

The repository for todo (default: `todo`) can be overridden by the environment variable `$GH_TODO_REPO`.

## Inspired by

- [yuler/gh-todo](https://github.com/yuler/gh-todo)
- [kawarimidoll/gh-q](https://github.com/kawarimidoll/gh-q)
