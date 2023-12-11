# namespaces.

In Pythong: a namespace package is a package that is split across
multiple directories on the filesystem. A namespace package may have
any number of parent directories, any number of which may have
__init__.py files (or may not). Namespace packages may even span
across multiple distributions.


It is a directory that contains only a __init__.py file.
 It is used to extend the Python namespace without
 introducing a new package. Namespace packages may be split across
 multiple directories located at different points in the filesystem.
 In this case, all of the directories must be included in the
 namespace package by placing a __init__.py file in each directory.
 The __init__.py files can be empty, but they must exist.
 https://packaging.python.org/guides/packaging-namespace-packages/


