# gh-todo

🗓 GitHub CLI extension for manipulating todo's managed by GitHub Issues using `fzf`.

![demo](https://user-images.githubusercontent.com/44780846/197148706-7f55ae2e-90c8-47fb-a6db-4ccdb342bc9e.gif)

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
