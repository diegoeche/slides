# A DIY Electronics Workshop #

This is a [WIP] DIY electronics workshop.

## Prerequisites ##

This guide was tested in Ubuntu 16.04. Some of the explanations might not apply.

### Install Arduino ###

1. Go to the [Arduino Website](https://www.arduino.cc/en/Main/Software)
2. Download the Arduino IDE

### Permission Denied Problem ###

```
$ sudo usermod -a -G dialout diegoeche
```

### Make sure you have the C340 kernel module ###

```
$ lsmod | egrep ch34
ch341                  16384  0
usbserial              45056  1 ch341
```