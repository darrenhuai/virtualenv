Switch the seed wheel image to its Windows short name whenever its files would pass the path length limits, counting the
separator and the shorter limit on directories, and read an image reused from an earlier run through that short name too,
so a deep ``--app-data`` folder no longer fails with ``WinError 206`` on the first run or on every run after it.
