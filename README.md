# VRDL_HW1_Bird_images_classification
6,033 bird images belonging to 200 bird species, e.g., tree sparrow or mockingbird (training: 3,000, test: 3,033)
External data is NOT allowed to train the model!

## Coding Environment
- Window 10
- Jupyter Notebook
- Google Colab

## Reproducing Submission
To reproduct the testing prediction, please follow the steps below:
1. [Jupyter Notebook environment](installation)
2. [Dataset](#dataset)
3. [Training](#training)
4. [Testing](#testing)

## Jupyter Notebook environment
Jupyter_Notebook_environment.txt contains all packages version of Jupyter Notebook
- Python 3.8.0

## Dataset
Because of using pytorch to predict the image, imagefolder could be used to generate training and testing data.
Imagefolder needs the image be arranged in the folder according to their labels, so we need to classify the image with folders.
Download the dataset from https://competitions.codalab.org/my/datasets/download/83f7141a-641e-4e32-8d0c-42b482457836.
create folder "data" .
create folder "images" in "data"put the training image into "training_images" folder.
create folder "training_images"、"training_labeled_images"、"testing_images"、"testing_labeled_images" in "images".
extract the training image into "training_images" folder.
extract the testing image into "testing_images" folder.
Then run the "image_label_classification" code will classify the image according to their labels.
