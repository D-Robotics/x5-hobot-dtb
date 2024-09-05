The method of generating dtbo.

```
dtc -I dts -O dtb -o ./dtoverlay_spi5_spidev.dtbo ./dtoverlay_spi5_spidev.dts
```


Example of writing in config.txt:

```
ion=ion_cma_size=0x20000000
ion=ion_reserved_size=0x40000000
ion=ion_carveout_size=0x40000000

```

Example of writing in config.txt:

```
dtoverlay=dtoverlay_pwm3

```

Note that there must be an empty line at the end, otherwise it will not be recognized.
