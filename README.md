# fullduplex_i2s
dts for fullduplex (in/out) i2s

- **Compile:**
`dtc -@ -H epapr -O dtb -o fullduplex_i2s.dtbo -Wno-unit_address_vs_reg fullduplex_i2s.dts`

- **Using:**
Add line
`dtoverlay=fullduplex_i2s`
in /boot/config.txt
