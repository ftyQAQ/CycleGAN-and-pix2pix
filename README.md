# CycleGAN-and-pix2pix
Unpaired and paired image-to-image translation.
## Installation
 ```
 torch>=1.4.0
torchvision>=0.5.0
dominate>=2.4.0
visdom>=0.1.8.8
  ```
## CycleGAN
### train
```
  python train.py --dataroot ./datasets/maps --name maps_cyclegan --model cycle_gan
 ```
### test
  ```
  python test.py --dataroot ./datasets/maps --name maps_cyclegan --model cycle_gan
   ```
## Pix2pix 
### train
```
python train.py --dataroot ./datasets/facades --name facades_pix2pix --model pix2pix --direction BtoA
```
### test
```
python test.py --dataroot ./datasets/facades --name facades_pix2pix --model pix2pix --direction BtoA
```
