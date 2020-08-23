# EEG_electrodes_with_spring_prongs

This repsitory is based on the following paper.

[M. Kimura, S. Nakatani, S.-I. Nishida, D. Taketoshi, and N. Araki, “3D Printable Dry EEG Electrodes with Coiled-Spring Prongs,” Sensors, vol. 20, no. 17, p. 4733, Aug. 2020.](https://www.mdpi.com/1424-8220/20/17/4733/htm)

Four stl files are available in this repository: 
- [spring.stl][1]
- [cover.stl][2]
- [spring_support.stl][3]
- [cover_support.stl][4]

[spring.stl][1] is a main material and [cover.stl][1] is a supplementary material that covers the prongs of the spring electrode. The stl files named ***_support.stl are included with the support material needed to print correctly on an SLA type 3D printer.
This electrode is designed for [Ultracortex Mark IV, OpenBCI](https://docs.openbci.com/docs/04AddOns/01-Headwear/MarkIV). They will print correctly if you use the equipment and print settings described in our paper.

# How To Print
The following is the procedure for making the electrodes, which are available to the public:
1. Download the [spring _support.stl][3] and [cover_support.stl][4] files.
2. Slice and print them with the print settings and resin shown in the paper. 
3. Wash the printed electrode with IPA and cut off the support with a nipper or similar tool referring to [spring.stl][1]. After that, allow the resin to cure sufficiently until it turns light blue.
4. Apply conductive paint all over the surface as shown in the figure (in the picture, a part of the side of the electrode is removed).
5. Attach the printed electrodes to the blue unit to which the stock electrodes were attached with the screws.

![electrodes print settings](https://github.com/1nakatan/omake/blob/master/img1.jpg "Slice and print")
![PAINT](https://github.com/1nakatan/omake/blob/master/img2.jpg "Cpnductive paste painting")

# CAUTION
It is very rare to succeed in the first printing. So, if you fail, try again with different print settings and resin temperature.
The published electrode structures, dimensions and print settings are optimized for  [blu by Siraya Tech](https://siraya.tech/products/blu-by-siraya-tech-for-lcd-resin-printers-1kg). If it does not print well, try changing the exposure time or bottom exposure time values. If the exposure time is too long, the print may become too thick, as shown below, and the print may not perform as it should.

![ERROR](https://github.com/1nakatan/omake/blob/master/img3.jpg "Exposure time is too long")

[1]:https://github.com/1nakatan/EEG_electrodes_with_coiled-spring_prongs/blob/master/spring.stl
[2]:https://github.com/1nakatan/EEG_electrodes_with_coiled-spring_prongs/blob/master/cover.stl
[3]:https://github.com/1nakatan/EEG_electrodes_with_coiled-spring_prongs/blob/master/spring_support.stl
[4]:https://github.com/1nakatan/EEG_electrodes_with_coiled-spring_prongs/blob/master/cover_support.stl
