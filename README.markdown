rbootx
------

`rbootx` is a small bash script that creates bootable backups for OS X,
using rsync.

Note that `rbootx` requires the latest rsync
[from Homebrew](https://github.com/Homebrew/homebrew-dupes/blob/master/rsync.rb).


USAGE
-----

    # the only required arguments are a source and a destination
    rbootx / /Volumes/Backup

    # dry run
    rbootx -n / /Volumes/Backup

    # supress the (minimal) non-error messages
    rbootx -q / /Volumes/Backup
