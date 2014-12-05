MariaDB 10.0 Software Collection
===============================

RPM sources for building MariaDB 10.0 SoftwareCollections.


How to build this package
-------------------------

You need to have `mariadb100-build` package installed and then build this
package usually or you define `scl` macro on mock/rpmbuild argument to
`mariadb100` this way:

    $ rpmbuild -ba --define 'scl mariadb100' mariadb.spec


