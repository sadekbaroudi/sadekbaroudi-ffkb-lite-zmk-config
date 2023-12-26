# ffkb lite

To build locally:
```
west init -l config; west update
west build --pristine -b "sadekbaroudi_svlinky" -s zmk/app/ -- -DSHIELD="sadekbaroudi_ffkb_lite"
