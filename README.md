Install Homebrew. 

Follow the steps on the https://treehouse.github.io/installation-guides/mac/homebrew to install Homebrew.

Download Node
    $ coverage run -m pytest
    $ coverage html
    $ open htmlcov/index.html

Running type checks with mypy:

::

  $ mypy medico

Test coverage
^^^^^^^^^^^^^

To run the tests, check your test coverage, and generate an HTML coverage report::

    $ coverage run -m pytest
    $ coverage html
    $ open htmlcov/index.html

Running tests with py.test
~~~~~~~~~~~~~~~~~~~~~~~~~~

::

  $ pytest

Live reloading and Sass CSS compilation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
