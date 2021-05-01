# Computational-Creativity
QMUL Coursework

CNN_StyleTransfer.ipynb first needs to be ran in order to get the stylized image which then can be fed into the image caption model. All the instructions to run the code has been given in CNN_StyleTransfer.ipynb notebook.

I've used me.jpg as a original content image and fire.jpg as a style image. 

The CNN_StyleTransfer.ipynb needs to be ran on Google Colab in order to use Colab form tools. Flask has also been used to create a web UI to upload the content and style image. Warning: The CNN_StyleTransfer.ipynb notebook will ask for the access to your Google drive and then will create the directories in which to upload the content and style images. 

I used Kaggle Kernel to build the image captioning model. Although this makes the workflow not seamless as it involves switching from google colab to kaggle kernel, kaggle offers a range of data repositories which can be very large for local storage. For example, Flickr8k is more than 1GB while glove 6b can be more than 800MB which I was able to get on Kaggle without any internet bandwidth. Therefore I'd recommend to use Kaggle Kernel to run the image captioning notebook. In order to use Kaggle Kernal, you need to setup Kaggle account at https://www.kaggle.com/ and here are the instructions to setup kaggle kernal https://www.kaggle.com/getting-started/44939

If you decide to run everything locally;

Flickr8k can be downloaded from the below link;
https://github.com/jbrownlee/Datasets/releases/tag/Flickr8k

Glove 6b embeddings used for pre-trained embedding in the image captioning can be downloaded from the below link;
https://nlp.stanford.edu/projects/glove/

GPU is required for the accelerated experimentations which is already provided in Google Colab and Kaggle Kernel. 

All the libraries imported on to the CNN_StyleTransfer.ipynb notebook can be ran on Google Colab and image captioning model's notebook on Kaggle Kernel. Flask library has been installed to run on Google Colab. Installation command is stated on to the CNN_StyleTransfer.ipynb notebook. 

If you decide to run the notebooks locally, I suggest to use pip package manager.
