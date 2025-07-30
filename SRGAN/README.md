SRGAN is the implementation of the paper https://arxiv.org/abs/1609.04802
The training has been done on DIV2k Dataset for approx. 5000 epochs with learning rate of 1e-4
From High Resolution Image patches of size 96 * 96 has been centre cropped and used as High Resolution Image.
HR image(96*96) has been downscaled by factor of 4 to obtain Low Resolution image
LR image(24*24) is then passed through SRGAN implementation to obtain Super Resolutio(SR) image.

Results are comparable

LR Image
HR Image
SR Image 
