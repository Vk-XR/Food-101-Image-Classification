# Food-101-Image-Classification
A milestone project created as a part of Daniel Bourke's Tensorflow Course (on Udemy).
Provide it with an image path to a food picture, and it will tell what it thinks it is, from the 101 food classes it is trained on.

I installed tensorflow locally on my machine and trained it using an Nvidia GTX 1650 GPU.
I provided the libraries required in `requirements.txt` file.

The model training time was ~75 minutes or 5 iterations on all of training data.
I was able to achieve 79% top-1 accuracy at most.

The aim was to beat the **DeepFood** paper - `https://arxiv.org/ftp/arxiv/papers/1606/1606.05675.pdf`, i.e. 77.4% top-1 accuracy.

I shall be trying to beat it using various other transfer learning models. My aim would be to beat it using as light model as possible.
