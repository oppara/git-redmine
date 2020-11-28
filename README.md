# git-redmine

Open the relevant Redmine issues page.

## Description

If the name of Git branch includes the Redmine issue number like bellow, display the issue page in your browser.

- 123_foo
- 456-bar
- baz789

## Requirement

* macOS

## Usage

While in the Git branch directory

```
$ git redmine
```

## Install

1. Place it in a directory in your path.
2. Specify Redmine issues URL. (The `git-config` settings take precedence.)
```
$ echo "export GIT_REDMINE_URL=https://your.redmine.example.com/issues/" >> /path/to/your/profile
```
or 
```
$ git config --global git-redmine.url "https://your.redmine.example.com/issues/"
```
or 
```
$ git config git-redmine.url "https://your.redmine.example.com/issues/"
```


## ToDo

* [ ] Windows support.
* [ ] Linux support.
* [ ] Create Homebrew formula.

## Licence

MIT

## Author

[oppara](https://github.com/oppara)
