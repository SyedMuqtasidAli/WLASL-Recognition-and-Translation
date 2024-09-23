# WLASL-Recognition-and-Translation

This repository contains the "WLASL Recognition and Translation", employing the `WLASL` dataset descriped in "Word-level Deep Sign Language Recognition from Video: A New Large-scale Dataset and Methods Comparison" by Dongxu Li.


>The project uses Cuda and pytorch, hence a system with NVIDIA graphics is required. Also, to run the system a minimum of 4-5 Gb of dedicated GPU Memory is needed.


### Download Dataset
-----------------

The dataset used in this project is the "WLASL" dataset and it can be found [here](https://www.kaggle.com/datasets/utsavk02/wlasl-complete) on Kaggle

Download the dataset and place it in data/ (in the same path as WLASL directory)

### Steps to Run
-----------------

To run the project follow the steps

1. Clone the repo

 ```
 
 git clone https://github.com/alanjeremiah/WLASL-Recognition-and-Translation.git
 
 ```
 
2. Install the packages mentioned in the requirements.txt file


> Note: Need to install the correct compatible version of the cudatoolkit with pytorch. The compatible version with the command line can be found [here](https://pytorch.org/get-started/locally/). Below is the CLI used in this project


```

conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch

```

3. Open the WLASL/I3D folder and unzip the NLP folder in that path

4. Open the run.py file to run the application

```

python run.py

```

### Model
-----------------

This repo uses the I3D model. To train the model, view the original "WLASL" repo [here](https://github.com/dxli94/WLASL/blob/master/README.md)

### NLP
-----------------

The NLP models used in this project are the `KeyToText` and the `NGram` model. 

The KeyToText was built over T5 model by Gagan, the repo can be found [here](https://github.com/gagan3012/keytotext)

### Demo
-----------------

The end results of the project looks like this. 

The conversion of `Sign language` to Spoken Language.




https://user-images.githubusercontent.com/69314264/168775253-93a68a4c-8a22-4475-81f3-37393add6653.mp4


[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:muqtasid5266@gmail.com)

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/923176517525)


