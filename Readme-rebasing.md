## Add remote upstream repo which hugo-clarity

```
git remote add upstream https://github.com/chipzoller/hugo-clarity.git   
```

## Fetch all the branches of that remote into remote-tracking branches, such as upstream/master:

```
git fetch upstream
```

## rebase your branch
git rebase upstream/master


## git clone recursively 

git clone --recurse-submodules https://github.com/chipzoller/hugo-clarity.git