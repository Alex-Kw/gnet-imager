# gnet-imager
linux based, open source DD wrapper for preparing CF card for taito G-net use.

THIS CURRENTLY DEFAULTS TO /dev/sdb. IF YOU HAVE MORE THAN ONE INTERNAL DRIVE YOU NEED TO EDIT THE SCRIPT.

Known issues or planned improvements:

- Detect CF type card media, to avoid possible risk of overwriting the wrong drive.

- Potentially see if a local copy of chdman could be used, to support CHD in addition to raw disk image.
