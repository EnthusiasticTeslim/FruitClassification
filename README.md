# PassionFruit
This repository contains my submission to the [PassionFruit challenge](https://zindi.africa/competitions/passion-fruit-disease-detection-indabax-cameroon/leaderboard) organzing by IndabaX Cameroon on [Zindi](https://zindi.africa/). 

In this project, I develop multi-class classification (3 classes: healthy, brownspot, woodiness) using 
1) conventional CNN
2) a pretrained RESNET model.  

## Interested?

To get started with the repository, follow these steps:

1. Sign up for the challenge to access the Images.zip data. 
2. Download the [`Passionfruit.ipynb`](Passionfruit.ipynb).
3. Modify the paths (e.g.` Images.zip` path) in notebook accordingly.

Feel free to contribute, open issues, or submit pull requests if you have any improvements or ideas to share!

## Plan
- [x] Resize image to (224 x 224)
- [x] Normalize image
- [x] Train a conventional CNN model
- [x] Apply transfer learning
- [] Assess if the initial assumption of well sampled data is wrong
- [] Data augumentation

## Appreciation
This solution is made possible by learnings from the [Applied AI Lab: Deep Learning for Computer Vision](https://www.wqu.edu/ai-lab-computer-vision) course by WorldQuant University. 