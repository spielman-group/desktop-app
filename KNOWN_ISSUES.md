# Known issues

- `shell.py`, Linux launcher reinstall: an existing symlink is removed only under if verbose, so quiet reinstallation can fail with FileExistsError (source review; not executed).
- `windows.py`, unredirect_appdata: custom shortcut paths outside AppData fail relative_to even though install accepts a custom path (source review; not tested on Windows).
