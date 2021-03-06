# travis_gcc_cpp11

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp11.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp11)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:

 * Build system: none
 * C++ compiler: `gcc`
 * C++ version: `C++11`
 * Libraries: `STL` only
 * Code coverage: none
 * Source: one single file, `main.cpp`

Less complex builds:

 * Use C++98: [travis_gcc_cpp98](https://www.github.com/richelbilderbeek/travis_gcc_cpp98)

Equally complex builds:

 * Use clang instead of GCC: [travis_clang_cpp11](https://www.github.com/richelbilderbeek/travis_clang_cpp11)

More complex builds:

 * Use C++14: [travis_gcc_cpp14](https://www.github.com/richelbilderbeek/travis_gcc_cpp14)
 * Use C++17: [travis_gcc_cpp17](https://www.github.com/richelbilderbeek/travis_gcc_cpp17)
 * Add Coverity Scan: [travis_qmake_gcc_cpp98_coverity](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_coverity)
 * Use of `qmake`: [travis_qmake_gcc_cpp98](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98)
