# classifier
Bash script that classifies files in a folder

Usage:
```bash
classifier /folder/with/random/files [filename]
```
If `filename` is provided, only that file will be classified. This is for use with file system watchers.

If only `/folder/with/random/files` is provided, all files in that folder are classifed, non-recursively.
