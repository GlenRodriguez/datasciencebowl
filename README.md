# datasciencebowl Images
Using data from Kaggle https://www.kaggle.com/competitions/datasciencebowl

Here I will share some notebooks of this classification problem.

There are 121 classes of images (microscopic marine life and similars).

Only train and validation data, not leaderboard data, because leaderboard data is not available.

[SeaImages.ipynb](SeaImages.ipynb) : Input 192x192, Conv2D 32x3x3, MaxPool2D 2x2, Conv2D 64x3x3, MaxPool2D 2x2, Conv2D128x3x3, MaxPool2D 2x2, Faltten, Dense 512, ouput 121 
