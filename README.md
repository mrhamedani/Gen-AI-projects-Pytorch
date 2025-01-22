# Gen-AI-projects-Pytorch

**1. FashionMNIST-Classification:**
FashionMNIST database belongs to PyTorch and contains a large number of black and white photos of types of clothing (pants, jackets, etc.). In this project, the goal is to classify all kinds of clothes.Important features: 
- EarlyStop
- prediction


**2. FashionMNIST_GAN:** 
The dataset from the previous project has been reworked except that this time the goal is to generate images (not classification) using training.In this project, photos are made by Generative Adversarial Network method.Important features: 
- made discriminative and generative
- Real and fake data and labels
- Loss comparison discriminative and generative


**3. AnimeFaces_DCGAN:** 
In this project, the Kaggle dataset called AnimeFaces is used, which contains color photos of anime faces. And the goal of creating a photo is similar to the CNN method (DCGAN or Deep Convolutional Generative Adversarial Network).Important features:
- Professional model building with CNN
- color photos (3 channels)


**4. with_without_glasses_CGAN:** 
CGAN or Conditional Generative Adversarial Network is a type of Generative Adversarial Network (GAN) in which presentations are dependent on a specific condition or conditions. In this project, a dataset is used, which includes photos of people, some with glasses and others without glasses, and this feature is available in the CSV file. We try to produce photos of people with glasses and without glasses separately.Important features:
- Wasserstein GAN with Gradient Penalty(WGAN-GP)
- Using normal distribution for weighting
- Dataset preparation
- How to label CGAN
- save & load_state_dict
- Display photos in different modes (matplotlib)
  
