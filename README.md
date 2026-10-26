# stylophone

custom stylophone PCB

using [this guide](https://www.allaboutcircuits.com/projects/create-your-own-stylus-controlled-synthesizer/)

# PCB

PCB used will be 200mm by 150mm

## key footprints

each key has its own footprint (named P1-P7)

- 10.5mm border on the outside of the keys
- 1mm border between keys (there are 14 borders)
- every key is 11mm wide (there are 15 full keys across)
- each chamfer is 2mm x/y
- full-height keys are 35mm tall
- half-height keys (black keys) are 13mm tall
- footprint editor origin is at top left of key
- no rounding corners

**NOTE**: press E on a pad to edit it
- use [this link](https://forum.kicad.info/t/create-pad-from-selected-shapes-solved/32770) to figure out the pad footprint
- [also useful](https://learn.pcbcupid.com/pcb-design/design/kicad/custom-footprints-in-kicad)


# TODO

1. [ ] test concept on a breadboard
2. [ ] add custom footprints for `TP4`-`TP28` so that they look like a keyboard in the PCB
	- plan pad types for each key by annotating the example PCB
3. [ ] layout PCB
4. [ ] build BOM and order correct parts
5. [ ] order PCB
6. [ ] assemble PCB
7. [ ] test PCB
