## `gh merge-pr`
`gh merge-pr` is a GitHub CLI extension to squash and merge PRs but replacing the merge commit with the PR description.

## Usage

```bash
$ gh merge-pr --help

  usage:
    gh merge-pr [COMMANDS]

  commands:
    gh merge-pr               Squash and merges the PR associated to the current branch
    gh merge-pr <pr_number>   Squash and merges the given PR number

  [options]
    -h, --help                Display the help information
```

## Installation
Make sure you have `gh` and `git` installed.

Then run:
```bash
$ gh extension install aitorvs/gh-merge-pr
```

## License

This code is licensed under [The MIT License](./LICENSE).
