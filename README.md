# Gen-AI-projects-Pytorch

**1. FashionMNIST-Classification: (CV Easy)**            
FashionMNIST database belongs to PyTorch and contains a large number of black and white photos of types of clothing (pants, jackets, etc.). In this project, the goal is to classify all kinds of clothes.new Important features: 
- EarlyStop
- prediction


**2. FashionMNIST_GAN:(CV Easy)** 
The dataset from the previous project has been reworked except that this time the goal is to generate images (not classification) using training.In this project, photos are made by Generative Adversarial Network method.new Important features: 
- GAN architecture
- made discriminative and generative
- Real and fake data and labels
- Loss comparison discriminative and generative


**3. AnimeFaces_DCGAN:(CV intermediate)** 
In this project, the Kaggle dataset called AnimeFaces is used, which contains color photos of anime faces. And the goal of creating a photo is similar to the CNN method (DCGAN or Deep Convolutional Generative Adversarial Network).new Important features:
- DCGAN architecture
- Professional model building with CNN
- color photos (3 channels)


**4. with_without_glasses_CGAN: (CV hard)** 
CGAN or Conditional Generative Adversarial Network is a type of Generative Adversarial Network (GAN) in which presentations are dependent on a specific condition or conditions. In this project, a dataset is used, which includes photos of people, some with glasses and others without glasses, and this feature is available in the CSV file. We try to produce photos of people with glasses and without glasses separately.new Important features:
- Wasserstein GAN with Gradient Penalty(WGAN-GP)
- Using normal distribution for weighting
- Dataset preparation
- CGAN architecture
- save & load_state_dict
- Show photos in different modes (matplotlib)

**5_blonde_black_hair_CelebFaces:(CV hard)**
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

**6_MNIST_Autoencoder: (CV intermediate)**
The mnist dataset is made of 60,000 images of numbers 0 to 9. In this project, we try to generate these numbers twice using the Autoencoder method.new Important features:
- Autoencoder architecture
- The concept of latent space

**7.FashionMNIST.tensorboard: (CV Easy)**
This is a simple project that we just want to generate the FashionMNIST dataset by a neural network and check it in the tensorboard environment..new Important features:
- tensorboard --> Scaler ,Graph ,Embedding ,Image

**8.VAE_glasses: (CV intermediate)**
In this project, we will again use the dataset with glasses and without glasses, but with the VAE (Variational Autoencoder) model. This model is similar to the normal Autoencoder, but has some new items.new Important features:
- loss = reconstruction_loss + kl
- VAE architecture
- eval methode
- weight_decay item in optimaizer

**9.TextGenerationLSTM: (NLP hard)**
In this project, LSTM model is used and the dataset is Anakarnina book by Telestoy. LSTM (Long Short-Term Memory) is a type of recurrent neural network(RNN) designed to process sequential data and is capable of preserving both long-term and short-term dependencies in the data.
The goal is to generate text using the dataset in exchange for a prompt.new Important features:
- LSTM architecture in Pytorch
- Clean text and tokenize words
- Build an LSTM model 
- Generate text with the trained LSTM model

**Attached**
In the continuation of this project, the subject of creativity has also been added to the model with the following two subjects:
- Temperature
- top-K sampling

**10.Skorch.Diabetes:**
Here, using the diabetes dataset, we just want to use the hyperparameter tuning feature.
pytorch does not have this method. But using skorch, which uses scikit-lesrn, we select the best hyperparameters.new Important features:
- gride.cv_results
- NeuralNetClassifier
- hyperparameter tuning

