Flask-Markdown Changelog
========================

Here you can see the full list of changes between each Flask-Markdown release.


Version 0.5 (Future)
-----------

This will bump the version as documentation/usage will change with new, more modern-Flask package name.

Planned Changes
+++++++++++++++
- changing package from ``flaskext`` to ``flask-markdown``.
- replacing test suite with `pytest <https://docs.pytest.org/>`_ (from nose2, which 
  is `somewhat old these days <https://docs.nose2.io/en/latest/#nose2-vs-pytest>`_)

Version 0.4.1
-------------

Fixed
+++++
- Fixes issue with DeprecationWarnings caused by ``evalcontextfilter`` 
  in `Jinja 3 <https://jinja.palletsprojects.com/en/3.0.x/changes/#version-3-0-0>`_


Version 0.4
-------------

**Forked from https://github.com/dcolish/flask-markdown**

Fixed
+++++
- Fixes issue with poetry due to lack of semver compliance in setup.py version attribute.