# Usage

    $ wget http://jaist.dl.sourceforge.net/project/regexxer/regexxer/0.10/regexxer-0.10.tar.bz2
    $ tar jxf regexxer-0.10.tar.bz2
    $ mv regexxer-0.10.tar.bz2 regexxer_0.10.orig.tar.bz2
    $ mkdir git; cd git
    $ git clone https://github.com/kumattau/regexxer-0.10.git
    $ find regexxer-0.10 ! -name "README.md" | cpio -pdumv ../
    $ cd ../regexxer-0.10
    $ debuild -us -uc

