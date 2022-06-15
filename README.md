# Plaket60
## Based on [Plain60 Flex Edition rev2.2](https://github.com/evyd13/plain60-flex-edition)

### Modification from Plain60 Flex Edition rev2.2

- Removing the speaker
- Removing the usb port
- Removing the flex cut
- Removing some compatibility in layout (keeping a Tsangan bottom row)

### Features
- Compatible with QMK Firmware and VIA Configurator (if you flash a VIA compatible .hex file)
- Required JST header for connection with daughterboard
- ESD protection and fuse
- No LEDs and no underglow
- Minimal layout support
- ISP header

### Supported layouts
![Supported layouts of the Plaket60 PCB](https://cdn.discordapp.com/attachments/831606808291704912/1006267790040244274/unknown.png)

### Bill of materials (BOM)
Amount is per PCB, multiply as needed.

| LCSC part # | Description | Value | Package  | Amount |
| ----------- | ----------- | ----- | -------- | ------:|
| C49678      | Capacitor   | 0.1uF | 0805     | 4      |
| C1779       | Capacitor   | 4.7uF | 0805     | 1      |
| C28323      | Capacitor   | 1uF   | 0805     | 1      |
| C109001     | Diode       |       | 0805     | 64     |
| C261942     | Fuse        |       | 0805     | 1      |
| C17414      | Resistor    | 10K   | 0805     | 2      |
| C212411     | Resistor    | 5.1K  | 0805     | 2      |
| C17561      | Resistor    | 22    | 0805     | 2      |
| C44854      | MCU         | 32U4  | QFP-44   | 1      |
| C7519       | ESD chip    |       | SOT23-6  | 1      |
| C341521     | Resonator   | 16MHz | SMD      | 1      |
| C92584      | Switch      |       | SMD      | 1      |
| C2845363    | JST         |       | SMD      | 1      |
