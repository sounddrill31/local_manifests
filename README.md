To initialize your local repository use
---------------------------------------

    git clone https://github.com/sounddrill31/local_manifests.git -b lineage-20-bacon .repo/local_manifests
    

Then to sync up:
----------------

    repo sync --force-sync -j $(nproc --all) --current-branch --no-tags --no-clone-bundle --optimized-fetch
