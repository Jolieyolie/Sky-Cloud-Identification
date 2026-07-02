# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Deep Learning-Based All-Sky Cloud Image Recognition

  - **[Link](https://www.mdpi.com/2073-4433/17/2/142)**
  - **Objective**: Cloud image recognition using deep learning
  - **Methods**: 256 cloud image observation data points collected by an all-sky imager from 3 to 30 November 2023, at the Tunchang County Meteorological Bureau in Hainan Province (19°21′N, 110°06′ E), CNN
  - **Outcomes**: 100% accuracy, 95% average accuracy in distinguishing between clear skies, stratus clouds, cumulus clouds, cirrus clouds
  - **Relation to the Project**: identification of different cloud types 

- **Source 2**: Artificial neural networks in automatic image classifications of cloud from ground-based observations using deep learning models

  - **[Link](https://rmets.onlinelibrary.wiley.com/doi/10.1002/qj.4865)**
  - **Objective**: Recognition of  cloud ground-photographs using deep learning
  - **Methods**: 200,000 cloud photographs from professional observers at meteorological stations of the Institute of Meteorology and Water Management–National Research Institute, CNN
  - **Outcomes**: 97.4% accuracy for classifying four common cloud genera: cirrus, cumulus, stratus, and clear sky & classification of 11 types
  - **Relation to the Project**: identification of different cloud types

- **Source 3**: Convolutional Neural Network for High-Resolution Cloud
Motion Prediction from Hemispheric Sky Images

  - **[Link](https://repo.uni-hannover.de/items/39643614-d1cd-4a94-934d-589d9eeccc5e)**
  - **Objective**: Predict cloud motion up to 10 minutes ahead
  - **Methods**: trained with 150,000 cloud pictures of hemispheric sky imager (HSI) at Institute of
Meteorology and Climatology (IMUK) of the Leibniz Universität Hannover, CNN
  - **Outcomes**: 94% accuracy for 1-minute prediction, decreasing to 37.8% for 10-minute prediciton
  - **Relation to the Project**: train CNN to predict motion/direction of clouds, for weather front prediction

- **Source 4**: Cloud Identification from All-sky Camera Data with Machine Learning

  - **[Link](https://arxiv.org/abs/2003.11109)**
  - **Objective**:identify opaque clouds (that bring bad weather) for protection of telescope equipement
  - **Methods**: first approach: ResNet (Residual NN) and 2nd: gradient-boosted tree-based model (lightGBM) trained with 2000 (1) and 1000 (1) images from Lowell Observatory's Discovery Channel Telescope
  - **Outcomes**: 85% accuracy in detecting clouds (ResNet) and 95% for 2nd approach
  - **Relation to the Project**: differentiating the color/shade of clouds

- **Source 5**: Deep learning-based identification of precipitation clouds from all-sky camera data for observatory safety

  - **[Link](https://www.sciencedirect.com/science/article/pii/S2666827025000234)**
  - **Objective**: automating the identification of precipitation clouds in all-sky camera data as a cloud warning system
  - **Methods**: using 2445 all-sky camera image archive of the Iranian National Observatory (INO) and trained with EfficientNet network (from Torchvision package), as well as LeNet, DeiT, and AlexNet
  - **Outcomes**: 99% accuracy in detecting rain fall potential, 96% accuracy for cloud coverage
  - **Relation to the Project**: create relationship in NN between cloud shading and rainfall potential
    
- **Source 6**: GitHub Repo: Cloud detection in sky images

  - **[Link](https://github.com/yuhao-nie/Cloud-dection-in-sky-images)**
  - **Objective**: Identify cloud pixels in sky images to support solar forecasting
  - **Methods**: algorithm from  Nie et al. (2020) study, with integration of NRBR (normalized red blue ratio) and CSL (clear sky library)
  - **Outcomes**: identification of several possible improvements: algorithm not self-adaptive when different camera is used, deep learning would be better option
  - **Relation to the Project**: distinguish between clear sky and clouds
