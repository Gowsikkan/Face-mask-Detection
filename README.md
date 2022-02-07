# Project Name
Face-mask-Detection

# Project Objective
The aim of this project is to create a video surveillance system to detect facemask to avoid the spread of Covid-19.

# Working
### Without mask
![Screenshot (376)](https://user-images.githubusercontent.com/66643168/152820623-38db8ed5-b487-4d61-8be6-9ad16df56dbb.png)

### With mask
![Screenshot (377)](https://user-images.githubusercontent.com/66643168/152820276-139d4bc1-10fa-4094-8e05-f44076c15a94.png)
# Packages Used
-   Tensorflow
-   OpenCV
-   Numpy
-   Imutils

# Technologies
- Python 3.7
- Pycharm

# Dataset
- maskdetector.model

# Installation
 Use can Install the packages for this application using
```sh
pip install -r requirements
```

# Separate environment
Create a viritual environment in order to avoid version errors between packages
```sh
pip install virtualenv
```

# Model Used 
- res10_300x300_ssd_iter_140000.caffemodel
- deploy.prototxt

# Output
The model will detect the masks and give us the output 
