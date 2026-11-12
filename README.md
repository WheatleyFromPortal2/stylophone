# stylophone

custom stylophone PCB

using [this guide](https://www.allaboutcircuits.com/projects/create-your-own-stylus-controlled-synthesizer/)

# PCB

PCB used will be 200mm by 150mm

## key footprints

each key has its own footprint (named P1-P7)

- 7mm border on the outside of the keys
- 1.5mm border between keys (there are 14 borders)
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

1. [x] add custom footprints for `TP4`-`TP28` so that they look like a keyboard in the PCB
	- plan pad types for each key by annotating the example PCB
2. [x] layout PCB
3. [x] build BOM and order correct parts
4. [x] route PCB
5. [ ] assemble PCB
    - need to make a stylus with a solder ball at the end
    - an alligator clip is way to abrasive and wears through the copper layer quickly
6. [ ] test PCB
