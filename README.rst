json2html
=========

Python wrapper to convert ``JSON object`` into a human readable ``HTML`` representation.

Features
--------

1. User-friendly readable format.
2. Easy to style for different purposes.

Installation
-------------

.. code-block:: bash
    $ pip install json2html
Or, Download `here <https://github.com/afzalimdad9/json2html/tarball/0.1>`_ and run ``python setup.py install`` after changing directory to `/json2html`

Example Usage
-------------

.. code-block:: python
    from json2html import *
    json2html = convert(json = {'name':'afzalimdad9','age':'21'})

Output:

.. code-block:: bash 
    <table border="1"><tr><th>age</th><td>21</td></tr><tr><th>name</th><td>afzalimdad9</td></tr></table>
