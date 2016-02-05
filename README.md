# blackwidow-linux

A Python3 script to enable the Macro and Fn keys under on the Razer Blackwidow keyboards under Linux. Works with newer devices that require Synapse 2.

### I do NOT own this software
> Origin: http://superuser.com/a/474595

### Prerequisites
 - Python3
 - PyUSB: https://walac.github.io/pyusb/ (*Not in Ubuntu/Debian repos, have to compile*)

Replace the Product ID in line 7:
```python
PRODUCT_ID = 0x11b #BlackWidow 2014
```
with the output from, specific to the keyboard model:
```sh
$ lsusb | grep Razer
```
