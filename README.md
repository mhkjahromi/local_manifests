# local_manifests

Mi5s room service

1.Place the roomservice:

cd ~/YOUR ROM NAME DIR && cd .repo && mkdir local_manifests && cd local_manifests && wget https://raw.githubusercontent.com/henmadx/local_manifests/9.0/capriservice.xml && cd ../..

2.Happy Sync :
Sync repo with roomservice: repo sync -f --force-sync --no-clone-bundle

or

repo sync --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken --force-sync -j8
