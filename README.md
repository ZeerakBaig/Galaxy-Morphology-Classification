# Galaxy-Morphology-Classification

Galaxies come in a variety of forms, dimensions, and hues. Galaxies need to be categorized to comprehend how the morphologies of galaxies connect to the physics that creates them. Therefore, classifying galaxy shapes is essential in understanding galaxy creation and development. Edwin Hubble first proposed the "Hubble Sequence" in 1926, also known as the "Hubble Tuning Fork," utilizing visual analysis of fewer than 400 galaxy photos. He also divided galaxies into three main categories: elliptical, spiral, and irregular. We still employ the "Hubble Sequence" nowadays. Astronomers have long updated the Hubble classification system and classified galaxies using visual observation.

Large-scale surveys like the Sloan Digital Sky Survey (SDSS) have produced many galaxy pictures in recent years. Astronomers' attempt to categorize this large number of photos is futile and time-consuming.  The main difficulty is developing a trustworthy method for doing morphological estimates from galactic pictures.

### Experiment Setup
This study aims to efficiently group different galaxy morphologies into the appropriate classifications. For Galaxy morphology classification, our first method employs a transformer-based architecture. The Vision Transformer, often known as ViT, is a method of classifying pictures that gives some areas of the image a Transformer-like shape. A typical Transformer encoder receives the sequence of vectors that results from dividing a picture into fixed-size patches, the linear embedding of each patch, and the addition of position embeddings. The conventional method of adding an extra, teachable "classification token" to the sequence is utilized to do classification.
Our second strategy is an adaptation of our first pipeline, in which a EfficientNet B7 architecture is utilized as a classifier rather than the vision transformer for side-by-side analysis.

### Tech Stack
[![AGPL License](https://img.shields.io/badge/Python-13.0-brightgreen)](http://www.gnu.org/licenses/agpl-3.0/)
![SkLearn](https://img.shields.io/badge/scikit-learn-red)
![SkLearn](https://img.shields.io/badge/tensorflow-2.9-brightgreen)
![SkLearn](https://img.shields.io/badge/Keras-2.10-green)

 ## Research Paper
 
 Research paper available at : [Research Paper Link](https://github.com/ZeerakBaig/Deep-Fake-Recognition/blob/main/ResearchPaper/ZeerakBaig_DeepFakeRecognition_VIT_2022.pdf)
