# GANs-for-data-augmentation
Image data augmentation using advanved CNN techniques.

Description/Overview:


Data augmentation using Generative adversarial networks(GANs)Data augmentation using Generative adversarial networks(GANs)
Oct 2023 - Dec 2023Oct 2023 - Dec 2023

Associated with University of Michigan-DearbornAssociated with University of Michigan-Dearborn
The goal of this project was to build a generative adversarial network (GAN) model to augment a lung X-ray image dataset for improved pneumonia detection. The skills and techniques demonstrated include:

Data Understanding and Preparation
- Loading and exploring 3883 28x28 pixel X-ray images using OpenCV and visualization with Matplotlib 
- Creating image batches and tensors as input for GAN using TensorFlow workflows
- Understanding class imbalance - only a small portion of images represented pneumonia cases

Model Development 
- Developing generator CNN to transform 100-dim noise vectors to 28x28 synthetic X-ray images
- Discriminator CNN design to classify real vs fake images 
- Leveraging transfer learning by using pre-trained InceptionV3 model to evaluate image quality

Custom Training Workflow
- Creating end-to-end pipeline with train step for generator and discriminator
- Use of GradientTape for automatic differentiation and finding loss gradients
- Testing performance using Adam and RMSProp optimizers 

Evaluations
- Tracking losses to prevent unstable training or mode collapse
- Inception score calculation using InceptionV3 model as reference
- Qualitative evaluation of generated images after 50 and 100 epochs

Key Results
- RMSProp optimizer showed more stable training with generator and discriminator losses 
- Better quality synthetic images generated compared to using Adam optimizer

In summary, this project developed expertise in CNN architectures, GAN frameworks, custom TensorFlow model development workflows and model diagnostic techniques - which are highly valued skills in the field of AI and machine learning. The final pneumonia detection model can be re-purposed in medical applications to improve diagnosis through data augmentation.
