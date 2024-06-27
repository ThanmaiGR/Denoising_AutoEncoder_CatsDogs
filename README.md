<h1>Overview</h1>

This project implements a Denoising Autoencoder to perform denoising on the Kaggle Cats and Dogs dataset. The goal is to train an autoencoder that can remove noise from images, thereby learning a robust feature representation.

<h1>Dataset</h1>
https://www.microsoft.com/en-us/download/details.aspx?id=54765

The dataset used for this project is the Kaggle Cats and Dogs dataset, which contains 25,000 images of cats and dogs. Each image is labeled as either a cat or a dog.
<h1>Prerequisites</h1>

Before running the code, ensure you have the following packages installed:
<ul>
    <li>Python 3.x</li>
    <li>PyTorch</li>
    <li>NumPy</li>
    <li>Matplotlib</li>
    <li>scikit-learn</li>
    <li>Pillow</li>
    <li>OpenCV</li>
</ul>
You can Install Pytorch from here
https://pytorch.org/<br>
The rest of the packages can be installed via this command<br>

##

    pip install numpy matplotlib scikit-learn pillow opencv-python

<h1>Data Preparation</h1>
Download the dataset and unzip it into the Datasets directory