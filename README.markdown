nikola
-----

`nikola` is a small bash script that creates bootable backups for OS X,
using rsync.


USAGE
-----

    # the only required arguments are a source and a destination
    nikola / /Volumes/Backup

    # dry run
    nikola -n / /Volumes/Backup

    # supress the (minimal) non-error messages
    nikola -q / /Volumes/Backup
