############
Demo project
############

python -m venv .venv && source .venv/bin/activate

python -m pip install -r requirements.txt

python manage.py runsslserver


`Demo folder in project's repository`_ contains a Django project:

* demo illustrates usage. Examples in documentation are imported from
  the demo.

* demo contains tests.

* demo can be used as a sandbox in order to try or develop the software.

Feel free to use the demo project as a sandbox. See :doc:`/contributing` for
details about development environment setup.


.. rubric:: Notes & references

.. target-notes::

.. _`demo folder in project's repository`:
   https://github.com/peopledoc/django-docusign/tree/master/demo/
