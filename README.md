## About

This script allows viewing diffs from git using Changes, the diff viewer tool for Mac OS X
(<http://changesapp.com/>).

## Usage

    gitchdiff [-r:] [repository]

## Examples

    $ gitchdiff
    # Same as:
    $ gitchdiff -rHEAD^:HEAD .

    $ gitchdiff -rHEAD^^:HEAD
    # Same as:
    $ gitchdiff -rHEAD^^:HEAD .

    $ gitchdiff -master:origin/master
    # Same as:
    $ gitchdiff -rmaster:origin/master .

    $ gitchdiff /path/to/git/repository
    # Same as:
    $ gitchdiff -rHEAD^:HEAD /path/to/git/repository

    $ gitchdiff -rHEAD^:HEAD /path/to/git/repository
    # Same as:
    $ gitchdiff -rHEAD^:HEAD /path/to/git/repository

## Authors

- Simon Menke
- Jonathan del Strother (optimizations)
- Josh Varner (error handling)