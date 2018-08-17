Ever wanted a massive number of internet coins? Dreamt of betting your friend 100Billion that they couldn't 1v1 you in the jungle? Wanted to just throw big numbers around to feel rich? Enter: Guildcoin.

Guildcoin has an exaggerated payout scheme that leads to bank acounts flush with zeros. Payouts are as follows:

Blocks 1-86,400         | 10,000,000 GLP

Blocks 86,401-259,200   | 3,000,000 GLP

Blocks 259,201-518,400  | 1,000,000 GLP

Blocks 518,401+         | 100,000 GLP



## Building Guildcoin

### On *nix

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/
* Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

**Advanced options:**

* Parallel build: run `make -j<number of threads>` instead of `make`.
* Debug build: run `make build-debug`.
* Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
* Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

### On Windows
Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run theas commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

And then do Build.
Good luck!
