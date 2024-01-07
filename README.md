To initialize your local repository use
---------------------------------------

    git clone https://github.com/sounddrill31/local_manifests.git -b lineage-oxygen .repo/local_manifests
    

Then to sync up:
----------------

    repo sync --force-sync -j8 --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken
