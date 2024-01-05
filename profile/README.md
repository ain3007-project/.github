
# **AIN3007 - Deep Learning for Medical Image Processing** - Term Project

This term project has been done as a part of the course AIN3007 - Deep Learning for Medical Image Processing at Bahçeşehir University. 

# Members

- Osman Faruk Bayram [github](https://github.com/osbm) [huggingface](https://huggingface.co/osbm)
- İclal Sönmez [github](https://github.com/iclalsonmez) [huggingface](https://huggingface.co/iclallalala)
- Alper Çakır [github](https://github.com/Alperitoo) [huggingface](https://huggingface.co/Alperitoo)

# Github Repos

- [ain3007-project/project-utils](https://github.com/ain3007-project/project-utils): This is a python package that contains utility functions for our project.
- [ain3007-project/preprocessing-data](https://github.com/ain3007-project/preprocessing-data): This repo contains the jupyter notebooks that we used to preprocess the data.


# Huggingface Repos

Our [huggingface account](https://huggingface.co/ain3007-project) contains datasets, models and spaces.

## Spaces

- [ain3007-project/ASAP-exporter](https://huggingface.co/spaces/ain3007-project/ASAP-exporter): A tool that lets us export annotations from ASAP to image files.

## Datasets

We have used the following datasets in our project. Most of these links are private and can only be accessed by the project members. We dont have the permission to share these datasets publicly. 

### Unprocessed datasets 

- [ain3007-project/raw-dataset](https://huggingface.co/datasets/ain3007-project/raw-dataset): Training dataset
- [ain3007-project/raw-internal-test-dataset](https://huggingface.co/datasets/ain3007-project/raw-internal-test-dataset): Internal test dataset
- [ain3007-project/raw-external-test-dataset](https://huggingface.co/datasets/ain3007-project/raw-external-test-dataset): External test dataset
- [Panda dataset](https://www.kaggle.com/competitions/prostate-cancer-grade-assessment/data): Prostate cANcer graDe Assessment (PANDA) Challenge dataset

### Processed datasets

2000 x 2000 thumbnails with original aspect ratio. (So there are images with shape 2000x1643, 2000x2000, 1445x2000 etc.)

- [ain3007-project/dataset-thumbnails-2000](https://huggingface.co/datasets/ain3007-project/dataset-thumbnails-2000): Training dataset
- [ain3007-project/test-dataset-thumbnails-2000](https://huggingface.co/datasets/ain3007-project/test-dataset-thumbnails-2000): Test dataset
- [ain3007-project/panda-dataset-thumbnails-2000](https://huggingface.co/datasets/ain3007-project/panda-dataset-thumbnails-2000): Panda dataset

512 x 512 thumbnails with white padding to make them square.

- [ain3007-project/dataset-thumbnails-512-padded-white](https://huggingface.co/datasets/ain3007-project/dataset-thumbnails-512-padded-white): Training dataset
- [ain3007-project/test-dataset-thumbnails-512-padded-white](https://huggingface.co/datasets/ain3007-project/test-dataset-thumbnails-512-padded-white): Test dataset
- [ain3007-project/panda-dataset-thumbnails-512-padded-white](https://huggingface.co/datasets/ain3007-project/panda-dataset-thumbnails-512-padded-white): Panda dataset
