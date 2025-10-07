- SRGAN is the implementation of the paper https://arxiv.org/abs/1609.04802
- The training has been done on DIV2k Dataset for approx. 5000 epochs with learning rate of 1e-4
- From High Resolution Image, patches of size 96 * 96 has been centre cropped and used as High Resolution Image(HR).
- HR image(96*96) has been downscaled by factor of 4 to obtain Low Resolution image(LR).
- LR image(24*24) is then passed through SRGAN implementation to obtain Super Resolution(SR) image.
- Weights can be found at: https://github.com/Balmukund151/Computer-Vision/releases/tag/Computer-Vision-Weights-Tag

- Results are comparable

LR Image 
<img width="1200" height="900" alt="ProGAN-Generated" src="https://github.com/Balmukund151/Computer-Vision/blob/main/SRGAN/Generated-Images/Low%20Resolution-Downscaled-by-factor-of-4-1.png"/>

HR Image
<img width="1200" height="900" alt="ProGAN-Generated" src="https://github.com/Balmukund151/Computer-Vision/blob/main/SRGAN/Generated-Images/High%20Resolution-Input-1.png"/>

SR Image
<img width="1200" height="900" alt="ProGAN-Generated" src="https://github.com/Balmukund151/Computer-Vision/blob/main/SRGAN/Generated-Images/Super%20Resolution-Generated-1.png"/>
