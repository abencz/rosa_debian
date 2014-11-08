# rosa releases

1. Clone rosa

        $ git clone git@github.com:abencz/rosa.git
        $ cd rosa
        $ git clone git@github.com:abencz/rosa_debian.git debian

1. Bump version

        $ dch -i

    or update changelog with explicit version

        $ dch -v

1. Build package

        $ cd ../
        $ debuild -S -sa

1. (optional) Release to Launchpad using [`dput`](https://help.launchpad.net/Packaging/PPA/Uploading)
