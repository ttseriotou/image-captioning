# Installation

Clone the git repo:

```$ git clone git@github.com:ttseriotou/image-captioning.git```

Create a conda environment:

```$ conda env create --file=image_captioning.yml```

Actviate the conda environment

```$ conda activate image_captioning```

# Model

The notebook defaults to the ```git-large-coco``` image captioning model for inference. There is though a wide range of different image captioning models in [Huggingface](https://huggingface.co/). Examples of such models are enlisted [here](https://huggingface.co/models?other=image-captioning)

# Data

Flickr Sample Data were obtained through:
https://www.kaggle.com/datasets/hsankesara/flickr-image-dataset

# Sources

Credits to the following sources for processing and GIT captioning:
https://www.kaggle.com/code/hsankesara/image-captioning

https://github.com/NielsRogge/Transformers-Tutorials/blob/master/GIT/Fine_tune_GIT_on_an_image_captioning_dataset.ipynb

https://huggingface.co/docs/transformers/model_doc/git
