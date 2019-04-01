# local_manifests

## Mi5s room service

**_1.Place The Roomservice:_**

```cd ~/ROM && cd .repo && mkdir local_manifests && cd local_manifests && wget https://raw.githubusercontent.com/henmadx/local_manifests/9.0/roomservice.xml && cd ../..```

**_2.Happy Sync :_**

```Sync repo with roomservice: repo sync -f --force-sync --no-clone-bundle```

or

```repo sync --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken --force-sync -j8```
