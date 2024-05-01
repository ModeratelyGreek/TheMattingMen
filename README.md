# MAS4115 Final Project
## Setup: Use the command pip install -r requirements.txt to install all dependencies
## Need Python version 3.12

In this project, we aim to tackle the problem of image matting, which is essentially seperating the foreground from the background of an image automatically. We use a closed-form matting solution implemented at https://github.com/MarcoForte/closed-form-matting based on the paper https://people.csail.mit.edu/alevin/papers/Matting-Levin-Lischinski-Weiss-CVPR06.pdf.
We use this closed-form matting algorithm along with a trained UNET on a large human potrait dataset (https://www.kaggle.com/datasets/laurentmih/aisegmentcom-matting-human-datasets?select=matting) and compare error metrics such as MSE, PSNR, and SAD to evaluate our two methods and compare the results.
