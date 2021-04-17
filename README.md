# Likes prediction for shitposting using Siamese Neural Networks (SNN) and Convolutional Neural Networks (CNN)
Using Siamese Neural Networks (SNN) to predict the number of likes of memes on Twitter. The data was obtained from [@ShitpostBot5000](https://twitter.com/ShitpostBot5000).

Two different architectures were trained, one using [MSE Loss](https://pytorch.org/docs/stable/generated/torch.nn.MSELoss.html) and the other using [Triplet Margin Loss](https://pytorch.org/docs/stable/generated/torch.nn.TripletMarginLoss.html). Three computer vision models were employed: AlexNet, ResNet and VGG16.

The process of data recollection is explained in [this](https://github.com/diegoasn/spb-tweets) repository.

## Content
* [`data`](https://anonfiles.com/90Z286r4u1/data_zip): contains all memes from training and testing datasets.
* [`models`](https://anonfiles.com/r3C291r6u5/models_zip): contains trained models.  

## Technologies
* Python v3.7
* Pytorch v1.8.1
* UMAP
* sklearn
* matplotlib
* pandas

**The data and model folders must be in the same directory as the notebooks**.  

**Note**: You will need a CUDA compatible GPU. 
