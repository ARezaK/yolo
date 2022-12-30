# yolo

`yolo`, a git alias.

## the alias

The alias runs this command:

```sh
git add -A && \
  git commit -am "`curl -s https://whatthecommit.com/index.txt `" && \
  git push -f origin master
```

## installation

```sh
curl -L https://raw.githubusercontent.com/ARezaK/yolo/master/install.sh | sudo bash
```

## contributing

* install as described in the previous step
* fork & clone the repo
* make your changes
* `git yolo`
