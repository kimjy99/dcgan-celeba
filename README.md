DCGAN (Deep Convolutional GAN) with CelebA dataset
=============

## Model
### Generator:  
> 1x1x(nz) → 4x4x1024 → 8x8x512 → 16x16x256 → 32x32x128 → 64x64x3
  
### Discriminator:  
> 64x64x3 → 32x32x64 → 16x16x128 → 8x8x256 → 4x4x512 → 1x1x1

### Gan Loss:  
> CrossEntrophy (= Vanilla GAN)
  
------------------
## Output Images  
![output_img](./images/DCGAN_CelebA_1.png)  

------------------
## Loss  
![loss_img](./images/DCGAN_CelebA_2.png)  

------------------
## Find latent vector for real images  
![latent_img](./images/DCGAN_CelebA_3.png)  
  
## Linearly mapping two images  
![mapping_img](./images/DCGAN_CelebA_4.png)  
![mapping_gif](./images/DCGAN_CelebA_anim.gif)  
