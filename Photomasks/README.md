# LipidWells v1.0.0 (Updated 01APR26 APM)

**Written by:** Adam Micolich

## Contents of the *Photomasks* folder

There is only a PDF file `Photomask Details.pdf`, which is an extract from Shuji Kojima's Ph.D. thesis that helps with understanding the design and layout of the mask set.

Due to the large files involved, the photomask GDSII files are available instead as a release asset here: https://github.com/AdMico/LipidWells/releases/tag/Photomasks

The release is a 238MB download, and the files require a suitable GDSII viewer, such as KLayout.

## Contents of the *Photomasks* release

The *Photomasks* release has 5 compressed RAR files containing the GDSII files for producing the photomasks used in this project. The details of the files are as follows:

`LipidWells Mask - Metal.gds`: This contains the first of the three masks used to make the OECT devices. This mask defines all the metallized parts of the device including the source and drain contacts, interconnects, and the various alignment markers for both subsequent photolithography steps as well as positioning of the glass block used to make the flow-cell. It is designed for use with a positive-tone resist such as Microchem's ECI-3012. Contrast = mostly metal, filled areas are transparent.

`LipidWells Mask - Channels_negative.gds`: This contains the second of the three masks used to make the OECT devices. This mask defines the 52 PEDOT:PSS channels on the coverslip. It is designed for a negative-tone resist such as AZ nLOF2020, as we used in our own device fabrication. Contrast = mostly metal, filled areas are transparent.

`LipidWells Mask - Channels_positive.gds`: This contains the second of the three masks used to make the OECT devices. This mask defines the 52 PEDOT:PSS channels on the coverslip. It is designed for positive-tone resist in cases where a negative-tone resist (e.g., AZ nLOF2020) is not available. Our experience has been that PEDOT:PSS channel performance is better if a negative-tone resist is used for patterning of the channels. Contrast = mostly glass, filled areas are metal.

`LipidWells Mask - Wells.gds`: This contains the third of the three masks used to make the OECT devices. This mask defines the hexagonally-close-packed array of 4 micron diameter wells in the active region of the device, as well as two large 'end-zones' for ensuring the fluoropolymer resist is removed at the contact pads for the spring pins. It is designed for use with a positive-tone resist such as Microchem's ECI-3012. Contrast = mostly metal, filled areas are transparent.

`LipidWells Mask - Tokyo.gds`: This is a modified version of the mask above used to make coverslips with only the fluoropolymer layer for more rapid testing of the fluidic aspects of the experiment. It contains only the hexagonally-close-packed array of 4 micron diameter wells in the active region of the device. Contrast = mostly metal, filled areas are transparent.

All masks are 4" soda-lime glass with the contrast specified as above, with chrome side down.

Note: The file `LipidWells Mask - Wells.gds` is extremely large when uncompressed (nearly 1GB in size).
