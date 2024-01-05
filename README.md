Image Super Resolution using ESRGAN
This repository contains code and resources for performing Image Super Resolution using ESRGAN (Enhanced Super-Resolution Generative Adversarial Network). ESRGAN is a deep learning model designed to enhance the resolution and quality of images.

We have extended ESRGAN to Real-ESRGAN, which is a more practical algorithm for real-world image restoration. For example, it can also remove annoying JPEG compression artifacts.

Requirements
numpy

tensorflow

tensorflow_hub

matplotlib

Installation
1) Installation Clone the repository:

git clone https://github.com/KHOPALE/img_upscaler.git

cd ESRGAN

2) Install dependencies:

pip install -r requirements.txt

Aternate method to run file
Run code.py file on google colab , run cell one bye one. always check image path.

Usage
1) Super-Resolution using Pre-trained Models

Use pre-trained ESRGAN models to perform super-resolution on images

!wget "https://user-images.githubusercontent.com/12981474/40157448-eff91f06-5953-11e8-9a37-f6b5693fa03f.png" -O original.png

Replace input.jpg with your input image file and output.jpg with the desired output file name. Adjust the model_path according to the pre-trained model you want to use.

2) Train ESRGAN Model (Optional)

python code.py

Results
Include sample images showing the results of super-resolution using ESRGAN. Provide visual comparisons with the original images to showcase the improvement in resolution and quality.

Acknowledgments
Install pretrain model like ESRGAN ect

