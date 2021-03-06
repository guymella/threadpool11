![threadpool11](https://raw.githubusercontent.com/tghosgor/threadpool11/misc/img/logo.png)
threadpool11
==========

### A fast, lock-free, cross-platform, full CPU utilizing thread pool implementation using C++11 features.

You can find the **dead simple API** documentation on header comments.

This project was initially developed in just a few hours of free time as I could not find a simple lightweight thread pooling library for my needs.

[Available on AUR](https://aur.archlinux.org/packages/threadpool11-git/).

## threadpool11 performance compared to OpenMP

Here is a result of OpenMP demo found in the tree.
> Your machine's hardware concurrency is 8

> threadpool11 execution took 6721 milliseconds.

> openmp execution took 10058 milliseconds.

> openmp execution (dynamic schedule) took 5505 milliseconds.

> gcc -v
> gcc version 8.2.1 20180831 (GCC)

Testing code can be found in project tree.

I will be glad to hear about the suggestions/ideas you have about the project, via the [issue reporting section](https://github.com/tghosgor/threadpool11/issues).

All non '_-dev_' branches are safe to use but prefer the latest version.
