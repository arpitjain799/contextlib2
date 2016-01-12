contextlib2 is a backport of the [standard library's contextlib
module](https://docs.python.org/3.5/library/contextlib.html) to
earlier Python versions.

It also serves as a real world proving ground for possible future
enhancements to the standard library version.

Development
-----------

contextlib2 currently has no dependencies.

Local testing is currently just a matter of running `python test_contextlib2.py`.

You can test against multiple versions of Python with [tox](http://tox.testrun.org/)):

    pip install tox
    tox

Continuous integration
----------------------

CI is set up in Codeship to run against PRs and commits.

[![Codeship Status for ncoghlan/contextlib2](https://codeship.com/projects/884e9500-3d1a-0133-3eb0-1abe7f570a4c/status?branch=default)](https://codeship.com/projects/102388)
[![codecov.io](https://codecov.io/bitbucket/ncoghlan/contextlib2/coverage.svg?branch=default)](https://codecov.io/bitbucket/ncoghlan/contextlib2?branch=default)