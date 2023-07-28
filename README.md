### ML-ISS2023
# Introduzione al Deep Learning per le Scienze della Salute
## HandsOn repository for the "Introduzione al Deep Learning per le Scienze della Salute"

***Table of contenents***

### Lesson 1 (theory): ***Introduction to machine learning***
Lecturer: Guido Gigante

- What’s machine learning? What’s deep learning?
- Recent achievements
- Categories of machine learning tasks
- Conceptual dimensions of machine learning

### Lesson 2 (hands-on): ***Supervised learning pipeline***
Lecturer: Andrea Ciardiello

- Data handling
- Model choice
- Training
- Performance evaluation
- review of python syntax:
  - Come si importano i moduli in python
  - Elementi di sintassi
    - Liste, dizionari, array, cicli, if statments
    - Salvare e caricare un file
    - Generazione numeri casuali con numpy
    - Plot di grafici 



### Lesson 3 (theory + hands-on): ***Unsupervised learning***
Lecturers: Guido Gigante and Andrea Ciardiello

- Cluster analysis
- Principal components
- Dimensional reduction
- Autoencoding

### Lesson 4 (theory): ***Deep learning basics***
Lecturer: Guido Gigante

Biological inspiration
From perceptron to deep networks
Convolutional neural networks
Transfer learning

### Lesson 5 (hands-on): ***Deep learning basics***
Lecturer: Andrea Ciardiello

- CNN on MNIST digit dataset
- Classification & autoencoding on MNIST
- Latent space analysis and visualisation
- Latent space clustering

### Lesson 6 (hands-on): ***Segmentation and object detection***
Lecturer: Andrea Ciardiello

- YOLO: an example of object detection with a pre-trained model


### Lesson 7 (theory + hands-on): ***Strategies to deal with “difficult” datasets***
Lecturers: Guido Gigante and Andrea Ciardiello

- Short short short introduction to MONAI (gestione dati medici (DICOM etc.), anonimization, upload; modelli pre-addestrati su dataset pubblici; tanti tipi di modelli (vincitori di challenge; “Model Zoo”); intergrazione con strumenti di segmentazione/labelling manuali usati dai clinici; supporto per calcolo distribuito)
Synthetic data augmentation
- More features than samples (the right way to do cross-validation, Hastie p. 241)
- Feature selection (not just correlation, also t-test, ANOVA - paper mandati da AC; + L1 and NOT L2; different simple “L1-regularized” models -> keep only the intersection of used features)
- One class is very rare (“imbalanced data”; Accuracy not right metric, AUC/ROC)
- Oversampling/undersampling, data point weighting, and data augmentation vs SMOTE (“oversampling con rumore”)

### Lesson 8 (theory + hands-on): ***Explainability***
Lecturer: Andrea Ciardiello
- Explainability in “classic machine learning”
- Feature importance
- Explainability for deep learning models
- Saliency & Influence

### Lesson 9 (theory): ***Complex systems and data science @ ISS***

- Alessandro Giuliani (ISS/DAMSA): Multiple facets of correlation matrices
- Evaristo Cisbani (ISS/TISP): Adversarial Examples on Deep Learning models for bio-medical imaging
