Testing
=======

Code without tests is broken by design. Please remember this and write tests ;)

This project runs tests inside Docker. It allows you to run tests locally with maximum isolation from the environment. It also gives you a simple way of adding new resources required for your tests.

Pytest
------

Use this command to run the tests:

.. code-block:: bash

    make test

This will run flake8 and after successful execution, the command will run a test suite with  `pytest`


mypy
----
Mypy is an optional static type checker for Python. We suggest you try it out as it allows you to catch some errors, write safer code and make refactoring of the code easier in the future.

To run mypy use this command:

.. code-block:: bash

    make mypy

Settings for mypy resides inside the mypy.ini file.

Read more:
----------

    - `pytest <https://docs.pytest.org/en/latest/contents.html>`_ -
        the official documentation for `pytest`

    - `mypy <https://mypy.readthedocs.io/en/latest/>`_ -
        the official documentation for `mypy`
