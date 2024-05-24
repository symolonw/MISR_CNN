## Multi-Image Super-Resolution CNN Architecture

by: William Symolon, Cihan Dagli, and Richard Threlkeld

## Description
This research proposes a deep learning architecture capable of enhancing lowresolution
NanoSat images to produce high-resolution imagery suitable for defense mission
planning and intelligence operations. The ability to make more effective use of NanoSat
technology expands the variety of imagery sources available to the Department of Defense
(DoD) and contributes to improved satellite redundancy and constellation resilience.

*Key words*: Deep Learning, super-resolution, computer vision, architecture

## CNN Architecture
![MISR_CNN_architecture](https://github.com/symolonw/MISR_CNN/assets/170744050/fe53794c-c1c3-4f9b-9e72-482268e21ce6)

## Network Testing

### Dependencies

!pip install torchviz \
!pip install graphviz \
!pip install torchview \
!pip install torchinfo

### Test
1. Clone this github repo
2. Upload misr_cnn.ipynb file to Google drvie and open with Google Colabratory
3. Load one of the provided pre-trained models (*.pth)
4. Create Allimages folder and upload your low-res test images
5. Results will be in ./output folder
