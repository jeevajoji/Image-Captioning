# Image-Captioning
Using ViT-BERT

First trained a model on Flickr8k dataset with 8000 images and coresponding 5 captions for each image , total of 40k captions .
But due to poor generalisation changed the dataset to Flickr30k dataset with 31000 images and but again due to lack of generalisation and less
accuracy , took a subset of MSCOCO dataset (30 million) of 156k images and its corresponding images , excluding some exceptions model 
turned out to be good with better generalisation and accuracy on unseen data.
