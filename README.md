# EEG_electrodes_with_spring_prongs

Four stl files are available in this repository: 
- spring_electrode.stl
- cover.stl
- spring_support.stl
- cover_support.stl

spring_electrode.stl is a main file and cover.stl is a supplementary material that covers the prongs of the spring electrode. The stl files named ***_support.stl are included with the support material needed to print correctly on an SLA type 3D printer.
This electrode is designed for [Ultracortex Mark IV, OpenBCI](https://docs.openbci.com/docs/04AddOns/01-Headwear/MarkIV). They will print correctly if you use the equipment and print settings described in our paper.

# How To Print
The following is the procedure for making the electrodes, which are available to the public:
1. Download the spring _support.stl and cover_support.stl files.
2. Slice and print them with the print settings and resin shown in the paper. 
3. Wash the printed electrode with IPA and cut off the support with a nipper or similar tool referring to spring electrode.stl. After that, allow the resin to cure sufficiently until it turns light blue.
4. Apply conductive paint all over the surface as shown in the figure (in the picture, a part of the side of the electrode is removed).
5. Attach the printed electrodes to the blue unit to which the stock electrodes were attached with the screws.

# CAUTION!
It is very rare to succeed in the first printing. So, if you fail, try again with different print settings and resin temperature.
The published electrode structures, dimensions and print settings are optimized for shirayatech blu. If shirayatech blu does not print well, try changing the exposure time or bottom exposure time values. If the exposure time is too long, the print may become too thick, as shown below, and the print may not perform as it should.
