s2-geometry-library-java
========================

A Fork of [pwheimann/s2-geometry-library-java](https://github.com/pwheimann/s2-geometry-library-java) - which again is a fork of https://code.google.com/p/s2-geometry-library-java/

Why?
====

The pwheimann version has everything you need (Maven dependency management, some upgrades, ...) except it doesn't support Java 7 anymore which is a problem if you run an off-the-mill Linux (Ubuntu, Mint, ...) because then you have to install Java 8.

Modifications to the pwheimann version
======================================

- Changes in tests to support Java 7 syntax
- Minor changes in doc strings (did you know that all area measurements are in [steradians](https://en.wikipedia.org/wiki/Steradian) and line measures in its 1d equivalent?)
