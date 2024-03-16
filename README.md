# Report Status of Multiple Git Repos at Once

Script to check the status of all repos in a directory.
Prevents having to check each repo individually.

Usage:

```bash
show-status.sh [directory]
```

This will run `git status` on each repo under the directory specified. If called with no directory provided it will default to the current directory.

<https://gist.github.com/mzabriskie/6631607>
