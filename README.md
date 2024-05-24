## Multi-Image Super-Resolution (MISR) Convolutional Neural Network (CNN) Architecture

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

`!pip install torchviz` \
`!pip install graphviz` \
`!pip install torchview` \
`!pip install torchinfo`

### Test
1. Clone this github repo

`git clone https://github.com/symolonw/MISR_CNN` \
`cd MISR_CNN`
   
3. Upload `misr_cnn_test.ipynb` file to Google drvie and open with Google Colabratory
4. Load one of the provided pre-trained models (*.pth) in ./models folder
5. Create ./Allimages folder and upload your low-res test images
6. Run `misr_cnn_test.ipynb` file
7. Results will be in ./Output folder

## Sample training output
![Arena_psnr_30_81](https://github.com/symolonw/MISR_CNN/assets/170744050/d8890e77-a06e-4850-8a97-c4caafa72d7c)
*Donbass Arena, Donetsk Ukraine*

![Planes_psnr_31_55](https://github.com/symolonw/MISR_CNN/assets/170744050/1c1d8690-e15e-48d4-884d-0d2997c1c815)
*Kandahar International Airport, Afghanistan*

## Sample validation output
![adamW_planes_compare](https://github.com/symolonw/MISR_CNN/assets/170744050/bf5a8f7b-a201-4343-803d-254bb54dd487)
*Kandahar International Airport, Afghanistan*

## Future Work
* Develop modified training and testing datasets that contain images with lower initial resolutions
* Expand the current training/testing datasets to include more variety of terrain types and feature complexity
* Develop a MISR Generative Adversarial Network architecture
* Combine various network types in series; e.g. a series architecture that includes a MISR CNN, followed by a SISR GAN
