## gitr - A simple tool to clone specified repositories

#### Usage:

`./gitr [-s]-u [GitHub username] -r [repo#1] -r [repo#n] [-p [path to clone to]]`

Specify as many repos as needed with multiple -r flags.

You can add the 's' flag before the -u flag (or anywhere you like) to download over SSH instead of the default setting, HTTPS:

`./gitr -su [GitHub username] -r [repo#1] -r [repo#n]`

*Note that if a path is not specified, your current working directory will be used instead!*
