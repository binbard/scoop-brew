# brew

Scoop bucket containing community-maintained packages.

## Add this bucket from a clone

```powershell
$bucketUrl = (git remote get-url origin) -replace '\.git$', ''
scoop bucket add brew $bucketUrl
```

## Install an app

```powershell
scoop install brew/markpad
```
