# Git log

The command `git log` can have its output formatted in many ways. Most of these come in the form of flags.

> [!tldr] Quick use command
> ```
> git log --graph --oneline --decorate
> ```

### Oneline

The `--oneline` flag condenses each commit to a single line. By default, it defaults only the commit ID and the first line of the commit message.

> [!tip]
> This is very useful for getting a high-level overview of your project.
### Decorating

The `--decorate` flag makes `git log` display all of the references (e.g., branches, tags, etc) that point to each commit.

### Graphs

	The `--graph` option draws an ASCII graph representing the branch structure of the commit history. This is commonly used in conjunction with the `--oneline` and `--decorate` commands to make it easier to see which commit belongs to which branch.
