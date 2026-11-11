Run the environment's own interpreter from ``pydoc.bat``. It called a bare ``python.exe``, which ``cmd.exe`` looks up in
the current directory and then on ``PATH``, so running ``Scripts\pydoc.bat`` without activating the environment
documented another Python's modules, or failed when no ``python.exe`` was on ``PATH``.
