# ESRGAN-Image-Super-Resolution-Project


Generator: A Residual-in-Residual Dense Block (RRDB)-based architecture.

![image](https://github.com/girivarakala1/ESRGAN-Image-Super-Resolution-Project/assets/130894864/cb394620-cbe0-4eee-a387-7c5aa4e9bf10)

Discriminator: A deeper architecture than traditional GANs to better distinguish between real and fake high-resolution images.

![image](https://github.com/girivarakala1/ESRGAN-Image-Super-Resolution-Project/assets/130894864/22424096-49a6-42b7-8b2d-05bb90192dfa)

Loss Functions: Combination of pixel-wise loss (L1 loss), perceptual loss, and adversarial loss

Objective: Set up the training loop with appropriate loss functions and optimizers.

Optimizers: Use Adam optimizer for both generator and discriminator. Loss Functions:

L1 loss for pixel-wise difference.

Perceptual loss using a pre-trained VGG network.

Adversarial loss using the discriminator output.

Objective: Evaluate the trained ESRGAN model and fine-tune if necessary.
Evaluation: Use metrics such as PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index) to evaluate the performance.

Fine-Tuning: Adjust hyperparameters, data augmentation, and model architecture as needed.

Average PSNR: 16.528246097086786, Average SSIM: 0.533117162864845
