# ihex2fw

Parser/loader for IHEX formatted data. Is pretty used on i2c Ilitek touchscreen fw. Format the fw using the following cmd:

```
 $ tail -n +3 input.hex > temp.hex
 $ ./ihex2fw temp.hex firmware/ilitek/ili251x.bin
 ```

References:
 - https://patchwork.kernel.org/project/linux-input/patch/20210819201759.2084481-2-marex@denx.de/