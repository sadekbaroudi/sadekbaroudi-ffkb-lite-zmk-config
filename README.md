# ffkb lite

To build locally:
```
west init -l config; west update
west build --pristine -b "sadekbaroudi_svlinky" -s zmk/app/ -- -DSHIELD="sadekbaroudi_ffkb_lite"
```

You can add additional vik modules, found here:  
https://github.com/petejohanson/sadekbaroudi-zmk-module/tree/main/boards/shields  

Example build string for ffkb lite with a svlinky and a ST7735 display:  
```
west build --pristine -b "sadekbaroudi_svlinky" -s zmk/app/ -- -DSHIELD="sadekbaroudi_ffkb_lite vik_st7735"
```