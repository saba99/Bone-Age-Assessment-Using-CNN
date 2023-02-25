# Bone Age Regression with Deep Learning

This is my code for the [I2A2 Bone Age Regression competition](https://www.kaggle.com/c/bone-age-regression). I learned a lot by building this pipeline from scratch and experimenting with different model architectures and optimizers. This was my first end-to-end image regression model, and it was very nice seeing my theoretical knowledge work in practice.

This competition was inspired by [RSNA's Bone Age challenge](https://www.kaggle.com/kmader/rsna-bone-age), in which given hand X-ray images, the model should predict the patient's bone age.

<img src="docs/ex1.png" width="250" height="320"> <img src="docs/ex2.png" width="250" height="320"> <img src="docs/ex3.png" width="250" height="320">
> X-ray images provided in the competition's dataset.

##Attention Images

## Results
<div align=center><img src="https://github.com/chenchao666/Bone-Age-Assessment/blob/master/img/img2.png" width="750" /></div>

## Requirements

See [requirements.txt](https://github.com/bryanlincoln/bone-age-regression/blob/master/requirements.txt).

## Usage

-   Download the requirements with `pip install -r requirements.txt`
-   Download the dataset and sample submission with `sh download_data.sh`. You may need to log in with your Kaggle account in order to do it.
-   Train the ResNet50 model with `python boneage.py`


