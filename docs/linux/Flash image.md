# Windows 10
1.  Download the Windows 10 ISO file from the Microsoft website.
2.  Insert a USB drive into your computer and identify the device name of the USB drive using the `lsblk` command.
3.  Unmount the USB drive using the `umount` command, followed by the device name of the USB drive. For example, if the device name of the USB drive is `/dev/sdb`, you would run the following command: `umount /dev/sdb`.
4.  Use the `dd` command to write the Windows 10 ISO file to the USB drive. The exact command will depend on the location of the ISO file and the device name of the USB drive. For example, if the ISO file is in the current directory and the device name of the USB drive is `/dev/sdb`, you would run the following command: `dd if=./windows10.iso of=/dev/sdb bs=4M status=progress && sync`
5.  After the `dd` command finishes writing the ISO file to the USB drive, you can safely remove the USB drive and use it to boot and install Windows 10 on your computer.