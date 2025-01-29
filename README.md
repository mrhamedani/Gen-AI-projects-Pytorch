# Gen-AI-projects-Pytorch

**1. FashionMNIST-Classification:**
FashionMNIST database belongs to PyTorch and contains a large number of black and white photos of types of clothing (pants, jackets, etc.). In this project, the goal is to classify all kinds of clothes.new Important features: 
- EarlyStop
- prediction


**2. FashionMNIST_GAN:** 
The dataset from the previous project has been reworked except that this time the goal is to generate images (not classification) using training.In this project, photos are made by Generative Adversarial Network method.new Important features: 
- GAN architecture
- made discriminative and generative
- Real and fake data and labels
- Loss comparison discriminative and generative


**3. AnimeFaces_DCGAN:** 
In this project, the Kaggle dataset called AnimeFaces is used, which contains color photos of anime faces. And the goal of creating a photo is similar to the CNN method (DCGAN or Deep Convolutional Generative Adversarial Network).new Important features:
- DCGAN architecture
- Professional model building with CNN
- color photos (3 channels)


**4. with_without_glasses_CGAN:** 
CGAN or Conditional Generative Adversarial Network is a type of Generative Adversarial Network (GAN) in which presentations are dependent on a specific condition or conditions. In this project, a dataset is used, which includes photos of people, some with glasses and others without glasses, and this feature is available in the CSV file. We try to produce photos of people with glasses and without glasses separately.new Important features:
- Wasserstein GAN with Gradient Penalty(WGAN-GP)
- Using normal distribution for weighting
- Dataset preparation
- CGAN architecture
- save & load_state_dict
- Show photos in different modes (matplotlib)

**5_blonde_black_hair_CelebFaces:**
CycleGAN is a style transfer model that performs image-to-image translation without requiring paired datasets. It has two Generators and two Discriminators and relies on a key concept called Cycle Consistency Loss.How CycleGAN Works:
The first generator converts an image from domain A (e.g., black hair) to domain B (e.g., blond hair).
The discriminator for B checks whether the output belongs to domain B.
The second generator converts the generated image back to domain A.
new Important features:
- CycleGAN architecture
- albumentations
- Dataset preparation by Dataset module
- ResidualBlock
- Downsampling & Upsampling
- Auto Mixed Precision

