A ``--pip`` or ``--setuptools`` version spelled differently from the wheel's, such as ``v26.3``, ``26.3.0`` or ``26.3``
with a trailing space or carriage return, now selects the bundled or cached ``26.3`` wheel. virtualenv used to download
it again, which failed offline, and rejected a value with surrounding whitespace only after creating the environment.
