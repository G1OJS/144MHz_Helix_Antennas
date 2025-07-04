# 144MHz_Helix_Antennas
## Compact horizontally polarized antennas inspired by W6NBC 

|    |    |
|---|---|
|![W6NBC Helix](https://github.com/user-attachments/assets/590b61c4-002f-4fd5-9dc4-4fa45d7e62c9) | ![chimney](https://github.com/user-attachments/assets/ef7cee62-7876-4a52-bae3-d5f5c36a9aed)|

Above is my first build of a helix antenna described in [W6NBC's paper in QST](https://w6nbc.com/articles/2011-06QST2mhelices.pdf). Roughly speaking it would fit in a 170mm sided cube, and it definitely fits inside the non-functional decorative GRP chimney pot on my house (i.e. right at the top in the circular pot, not the square section below).

This repo is new as of 30th June 2025 and will be developed if my experiments with stacking these antennas is successful. Amongst the folders are NEC files and results, though as John says in his article, don't take dimensions from the NEC files as definitive as your helix will use different materials and potentially be a slightly different size. The overall length of conductor, at around half a wavelength, seems to be an important constant. All TBC.

Another job is to turn the 4nec2 output into a file I can use to look at how polarisation resolves into V, H, LHCP and RHCP against position around the antenna.

I've now also built a pair of helixes, closely stacked with opposite 'sense' to cancel the vertical polarisation and force it into horizontal - which seems to work well: [folder link](https://github.com/G1OJS/144MHz_Helix_Antennas/tree/main/G1OJS_Contraspiral)

The helix in the picture is fed via a 1:1 transmission line balun rather than using a common mode inductance with an unknown distributed capacitance, because the former seem to me to be more reliably repeatable.
