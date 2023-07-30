# isodrive (configfs)

## Usage

Run `su` to be able to access and use the `isodrive` command.

```
isodrive [FILE]... [OPTION]...
Mounts the given FILE as a bootable device using configfs.
Run without any arguments to unmount any mounted files and display this help message.

Optional arguments:
-rw              Mounts the file in read write mode.
-cdrom           Mounts the file as a cdrom.
-configfs        Forces the app to use configfs.
-usbgadget       Forces the app to use usb_gadget.
```

## Os Support
* Should support almost every bootable OS images, but for those who don't work or need extra steps, are documented in the [WIKI](https://github.com/nitanmarcel/isodrive/wiki)

## Source Code
* https://github.com/nitanmarcel/isodrive-magisk

## Credits

Inspired by https://github.com/fredldotme/ISODriveUT
