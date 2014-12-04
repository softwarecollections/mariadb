MariaDB 5.5 Software Collection
===============================

RPM sources for building MariaDB 5.5 SoftwareCollections.


How to build this package
-------------------------

You need to have `mariadb55-build` package installed and then build this
package usually or you define `scl` macro on mock/rpmbuild argument to
`mariadb55` this way:

    $ rpmbuild -ba --define 'scl mariadb55' mariadb.spec


