# Roundware Contribution Help

## Assigning Copyright

## Github fork procedures

Setup your fork with the upstream repo as a remote:

```bash
git clone git@github.com:username/roundware-android.git
cd roundware-android
git remote add upstream https://github.com/roundware/roundware-android.git
```

Updating your develop branch
```bash
git checkout develop
git remote update --prune
git pull upstream develop
git push origin develop
```
