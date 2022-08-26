# clone with submodules
```
git clone https://github.com/pcs-highschool/_combine --recurse-submodules 
```

## submodule update to remote
```
git submodule foreach 'git add .'
git submodule foreach 'git commit -m "commmit message"'
git push --recurse-submodules=on-demand
```

## get updated submodules
```
git submodule update --remote
git submodule foreach 'composer dump'
```

## submodule edit
edit ```.gitmodules``` file in project root

