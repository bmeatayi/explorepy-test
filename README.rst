========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/explorepy-test/badge/?style=flat
    :target: https://readthedocs.org/projects/explorepy-test
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/bmeatayi/explorepy-test.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/bmeatayi/explorepy-test

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/bmeatayi/explorepy-test?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/bmeatayi/explorepy-test

.. |requires| image:: https://requires.io/github/bmeatayi/explorepy-test/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/bmeatayi/explorepy-test/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/bmeatayi/explorepy-test/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/bmeatayi/explorepy-test

.. |version| image:: https://img.shields.io/pypi/v/explorepy-test.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/explorepy-test

.. |commits-since| image:: https://img.shields.io/github/commits-since/bmeatayi/explorepy-test/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/bmeatayi/explorepy-test/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/explorepy-test.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/explorepy-test

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/explorepy-test.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/explorepy-test

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/explorepy-test.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/explorepy-test


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: MIT license

Installation
============

::

    pip install explorepy-test

Documentation
=============


https://explorepy-test.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
