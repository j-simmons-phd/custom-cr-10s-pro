# Custom CR-10s Pro
My current 3D printer, a Creality CR-10S Pro (somewhat modified from stock).

## Slicers Used

- [Cura v4.6.2](https://ultimaker.com/software/ultimaker-cura) for printing minis in PLA
- [SuperSlicer](https://github.com/supermerill/SuperSlicer) for general printing (including cosplay props) in PETG

## Profiles

### Cura Minis Profile (PLA)

- See profiles/curaMinisProfilePLA.curaprofile
- Based on [FDG Cura 4.6 Mini 4mmNozzle v1.10](https://www.dropbox.com/sh/vr9lkpjt6zw7s8s/AABhWEJUda0HREKn2GxWmOfSa/Cura%204.6/FDG_Cura4_6_Mini_4mmNozzle_V1-10.curaprofile?dl=0) by [Fat Dragon Games](http://www.fatdragongames.com/fdgfiles/)
- See [How to 3D print miniatures on a FDM printer](https://www.youtube.com/watch?v=AqEWl51s9Rw) on YouTube for explanation of the settings
- My updates
    - Add generation of supports (hollow to minimize stresses when removing them)
	- Adding rafts to ensure adhesion when printing multiple minis at the same time (WIP)

### SuperSlicer General Profile (PETG)

- See profiles/SuperSlicer_General_PETG_config_bundle.ini (I have lost track of the full pedigress of these profiles, apologies to whomever posted the originals)
- My updates
	- Temperatures to account for PEX build surface
	- Infill settings (30% density and Gyroid pattern to prevent print head from knocking the part off of the build plate)

## Physical Modifications

### Wham Bam Systems Flexible Build System

- [Flexible Build System](https://whambamsystems.com/flexible-build-system)
- Using PEX Build Surface, [FAQ](https://whambamsystems.com/blog/f/build-surface-differences-settings-tips-and-maintenance) contains info on bed temperatures for different materials on the PEX build surface.

### Z axis (T8 Anti-Backlash Nuts)

- [BIQU T8 Anti Backlash Spring Loaded Nut](https://www.amazon.com/gp/product/B06XCCDD51)
- [Installation Video](https://www.youtube.com/watch?v=hG8X26UtLVw)
