# Mnist_Persian Classifier
We proposed a CNN network for Mnist Persian classification. We used framework pytorch==1.8.2.
## Dataset
MNIST persian image dataset includes a training set of 960 samples and a test set of 240 samples. Each sample is resized to 70*70 pixels on a RGB associated with a tag of 10 classes. 
Please download dataset from [here](https://drive.google.com/drive/folders/1--LGkYnr8Biq9iD0B445YZNC7MOq7Fds?usp=sharing)

## Train
to train the model please run the file `train.ipy`

## Pretrained model
Please download the weights from [here](https://drive.google.com/file/d/1CbouHYVoRUF8d_wC8i0D7SysXoA_DYpD/view?usp=sharing)  

## inference
to test the trained model, please run the following file:
`python inference.py --img_path --model_path --device`
