.. -*- coding: utf-8 -*-

Changes
-------

0.1 (2016-03-21)
~~~~~~~~~~~~~~~~

- First cut of the features

0.2 (2016-03-29)
~~~~~~~~~~~~~~~~

- use arrow functions to retain ``this`` were possible
- translate ``async/await``
- refactoring of the ``for`` loops
- add ability to subtranslate pieces of Python code or objects. Used
  to template the creation of ``Exception`` sublasses
- add support for param defaults and keyword arguments
- updated documentation

0.3 (2016-04-08)
~~~~~~~~~~~~~~~~

- updates to the documentation ( with some fixes made by Hugo Herter,
  Daniel Kopitchinski and ironmaniiith)
- Translate ``str(x)`` into ``x.toString()``
- Add support for properties and classmethods
- Translate ``__len__`` and ``__str__`` methods to ``get length()``
  and ``toString()``
- Add support for slices syntax to ``.slice()``
- Fixed two bugs in sourcemaps generation
- Fixed a bug in the ``inport ... from`` translation
- Correctly include BabelJS minimized code
- Fix transpiling of stage3 features
