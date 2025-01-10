# 3D_brain_segmentation
Hello! Welcome to the 3D Brain Segmentation model. This model is an image classifier, meant to separate 3D MRI T1 scans of the brain into four parts - background, grey matter, white matter, and cerebrospinal fluid.

Using the brain scans of 726 patients, we developed the data into a Convolutional Neural Network that segments the brain into different areas. This is a part of a project completed for the Art of Engineering course (ENGI1102), and comes with a video of me and my teammate, Eva, presenting our plan and results (to be added soon!)

We found the data on Kaggle. Feel free to take a look as I go through the ML cycle and perfect this model's performace. Here's the link to the dataset: https://www.kaggle.com/datasets/soroush361/3dbraintissuesegmentation

We had two attempts in building this project. In the first attempt, we neglected to consider all 3 axes of the images, and so our model struggled greatly, especially after the U-Net. So, in the second attempt, we reapproached the segmentation by considering all three axes.

To run the model:

Click one of the projects, the file either labeled "finalbme-6.ipynb" or "final-bme-project-2.ipynb"
Click the "Download raw file" button in the top right of the notebook.
Go to Kaggle and upload the file to a new notebook.
Download the dataset I used from Kaggle using the link above - note that the dataset is very large, as there are over 700 3D images and all inputs for our larger model are just over 80 GB.
Upload the file to your new notebook on Kaggle. You can upload the dataset on Google Colab by clicking on the file button to the left or on Kaggle using the input tab at the top.
Run all the cells and watch the model work! Follow along with my descriptions to get a feel for how/why I'm doing each step.
Thanks for stopping by - have a great day! :)
