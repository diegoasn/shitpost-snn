# Likes prediction for shitposting using Siamese Neural Networks (SNN) and Convolutional Neural Networks (CNN)
Using Siamese Neural Networks (SNN) to predict the number of likes of memes on Twitter. The data was obtained from [@ShitpostBot5000](https://twitter.com/ShitpostBot5000).

Two different architectures were trained, one using [MSE Loss](https://pytorch.org/docs/stable/generated/torch.nn.MSELoss.html) and the other using [Triplet Margin Loss](https://pytorch.org/docs/stable/generated/torch.nn.TripletMarginLoss.html). Three computer vision models were employed: AlexNet, ResNet and VGG16.

The process of data recollection is explained in [this](https://github.com/diegoasn/spb-tweets) repository.

## Content
Include the following directories:
* `data`: contains all memes from training and testing datasets.
* `models`: contains trained models.  

## Technologies
* Python v3.7
* Pytorch v1.8.1
* UMAP
* sklearn
* matplotlib
* pandas

**Note**: You will need a CUDA compatible GPU. 
