.. global.rst is loaded with every *.rst file of the project
   (as configured by conf.py, with the variable "rst_prolog")

.. Roles

.. role:: cpp(code)
    :language: c++

.. role:: raw-latex(raw)
    :format: latex


.. Substitutions

.. no-break whitespace
.. |nbws| unicode:: 0xA0
    :trim:

.. |hyphen| unicode:: U+2012

.. |endash| unicode:: U+2013

.. |emdash| unicode:: U+2014

.. begin double quote
.. |bdq| unicode:: U+201C
    :rtrim:

.. end double quote
.. |edq| unicode:: U+201D
    :ltrim:

.. |br| raw:: latex

    \newline



.. colors
   See https://stackoverflow.com/questions/32033158/create-a-role-font-color-in-sphinx-that-works-with-make-latexpdf
   The latex-macro is different than what is described on stackoverflow,
   see sphinxcronologic.sty for the setup

.. red of c++ types from code-highlighting
.. role:: ctypered

.. role:: cronoblue

.. role:: red

.. attention:: 

    This User Guide is under active development and is subject to major 
    changes.