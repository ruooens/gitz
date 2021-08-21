# gitz
Retain anonymity by faking your timezone in Git commit history.

## Usage
`gitz` is a wrapper around `git`, so all you need is to prepend your Git command line with `gitz timezone`:
```shell
$ gitz -0400 commit -m "BLAH BLAH BLAH"
```
