## SQLite-CPP Packaging ##

This project provides a script which will package SqliteModernCpp headers in a similar manner to the other `build-*` projects.  It contains as a submodule, [sqlite-cpp][sqlite-cpp-release] git project.  It also contains a copy of the [SQLite Amalgamation][sqlite-amalg-release].

[sqlite-cpp-release]: https://github.com/toonetown/sqlite-cpp
[sqlite-amalg-release]: https://sqlite.org/amalgamation.html

### Requirements ###

This library is header-only and the script just copies the headers into a package.

     
### Build Steps ###

You can package this by using the `build.sh` script:

    ./build.sh [/path/to/sqlite-cpp-dist] package </path/to/output/directory>

Run `./build.sh` itself to see details on its options.

You can modify the execution of the scripts by setting various environment variables.  See the script sources for lists of these variables.
