asocssap
========

All Sort Of Code Snippets Solving Algorithms Problems

Compiling
=========

To see a list of target and a short help on how to build issue the following command:

    cmake -P KRAL/builder.cmake

To generate the project a commmand like the following will do it:

    cmake -DT=testbed -DGENERATE=1 -P KRAL/builder.cmake

To compile it:

    cmake -DT=testbed -DCOMPILE=1 -P KRAL/builder.cmake

To build a target in a single step:

    cmake -DT=testbed -DBUILD=1 -P KRAL/builder.cmake

Running tests
=============

To run all the tests use the following command:

    projects/testbed-osx/euler/Debug/euler_tests

To run specific tests:
    
    projects/testbed-osx/euler/Debug/euler_tests --gtest_filter=problem_0019
