# test

Change 1

## Add Upstream

```sh
git remote add upstream git@github.com:BiltuDas1/test.git
```

## Fetch Upstream

```sh
git fetch upstream main
```

## Rebase Upstream

```sh
git pull upstream main --rebase
```

## If Conflict occurred then fix conflict and run

```sh
git add .
git rebase --continue
```

## If everything done then run

```sh
git push origin HEAD --force-with-lease
```
