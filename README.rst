cookiecutter-pelican-entry
==========================
Cookiecutter_ template to create a single-file reStructuredText_ Pelican_ page entry

Works around this issue: https://github.com/cookiecutter/cookiecutter/issues/35

Notes on usage
++++++++++++++
This uses a simple script to take the output file and move it up a directory.  This requires some caution when using:

#. The output filename could overwrite an existing file with the exact same name.
#. The directory name is a deliberately uncommon one (``__tmp__``), but it still must not exist in the directory where you run this cookiecutter template.

Alternatives
++++++++++++
- https://github.com/copier-org/copier
- https://github.com/bbugyi200/cookie

.. _cookiecutter: https://github.com/cookiecutter/cookiecutter
.. _restructuredtext: https://docutils.sourceforge.io/rst.html
.. _pelican: https://blog.getpelican.com/