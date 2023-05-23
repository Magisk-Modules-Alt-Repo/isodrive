# isodrive# isodrive (configfs)

**You need to be in `su` to use the `isodrive` commands**

usage:

* `isodrive {iso} {cdrom[0/1]} {readonly[1/0]}`

mount

* `sudo isodrive /full/path/to/file.iso`

umount

* `sudo isodrive`

mount (as cdrom)

* `sudo isodrive /full/path/to/file.iso 1 1`

mount (as read write)

* `sudo isodrive /full/path/to/file.iso 0 0`

## Os Support
* _Should support almost every bootable OS images, but for those who don't work or need extra steps, are documented in the [WIKI](https://github.com/nitanmarcel/isodrive/wiki)_

## Source Code
https://github.com/nitanmarcel/isodrive-magisk
## Credits

Inspired by https://github.com/fredldotme/ISODriveUT
