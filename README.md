# Do Androids Draw of Electric Sheep?

## Introduction
As you can see, the project was inspired by a science fiction novel: Do Androids Dream of Electric Sheep? For this project, I used the quick draw dataset from google, which has sketches drawn by different people from all over the world. I wanted to use GAN to allow the AI to draw its own sheep.

## Dataset and reference

Dataset: https://quickdraw.withgoogle.com/data
![quickdraw](https://github.com/zhangxiangna/coding3/raw/main/image/quickdraw.png "quickdraw")
Reference: https://github.com/HuiiJi/GAN_.py/tree/main

## Working Process

Firstly, this dataset was not in the image format or csv format that I was familiar with, so I formatted him and stored him in a folder in png format.

Then I started rewriting it with reference in jupyter notebook. But eventually, probably due to my keras version, the script made frequent errors during training, causing me to keep making changes until my code became so messed up that I had to reinstall my computer. After reinstalling my computer I decided to give up on it.

I finally chose this example as a reference because it is very concise, easy to understand and logical. The whole structure is divided into five parts: parameter configuration, network construction, data loading, training and validation. Through the study and learning of this code, I also basically understand the pattern of GAN image generation.


## Outputs
Here are some of the outputs of my work, and I think some of them have AI drawing sheep as well as humans do. I think it's a very lovely thing to see the AI drawing the sketches.
Epoch 71:
![71](https://github.com/zhangxiangna/coding3/blob/main/image/71.png "71")
