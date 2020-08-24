
# linuxcam

Tool that ease camera video streams checks and allows to install all requirements and setup a virtual camera to shows system desktop through it.

```bash
Usage: linuxcam [-h help] [-i install] [-l list] [-t test] [-d desktocam]

  -h, --help      : Show this message
  -i, --install   : Install usefull softwares
  -l, --list      : Detect available cameras
  -t, --test      : Check camera stream
  -d, --desktocam : Setup a virtual camera that shows system desktop
```

## Usage

First install all needed requirements:

```bash
sudo ./linuxcam -i
```

Launch the virtual desktop camera:

```bash
sudo ./linuxcam -d
```

Check the virtual desktop camera:

```bash
sudo ./linuxcam -t
```

## Notes

- This script ease installation of v4l2loopback in a Ubuntu distribution by signing the kernel module for Secure Boot enabled system.

