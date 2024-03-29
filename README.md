# Do Androids Draw of Electric Sheep?

## Introduction
As you can see, the project was inspired by a science fiction novel: Do Androids Dream of Electric Sheep? For this project, I used the quick draw dataset from google, which has sketches drawn by different people from all over the world. I wanted to use GAN to allow the AI to draw its own sheep.In the meantime, I'll console myself with my severe insomnia. Hopefully, so many sheep will make me sleep better.

View the vedio:https://www.youtube.com/watch?v=hc-frQ1fjaI

## Dataset and reference

Dataset: https://quickdraw.withgoogle.com/data
![quickdraw](https://github.com/zhangxiangna/coding3/raw/main/image/quickdraw.png "quickdraw")
Reference: https://github.com/HuiiJi/GAN_.py/tree/main

## Working Process

Firstly, this dataset was not in the image format or csv format that I was familiar with, so I formatted him and stored him in a folder in png format.

Then I started rewriting it with reference in jupyter notebook. But eventually, probably due to my keras version, the script made frequent errors during training, causing me to keep making changes until my code became so messed up that I had to reinstall my computer. After reinstalling my computer I decided to give up on it.

![3575596be43e5a60c70bea5a1cede83](https://github.com/zhangxiangna/coding3/raw/main/image/3575596be43e5a60c70bea5a1cede83.png "3575596be43e5a60c70bea5a1cede83")

I finally chose this example as a reference because it is very concise, easy to understand and logical. The whole structure is divided into five parts: parameter configuration, network construction, data loading, training and validation. Through the study and learning of this code, I also basically understand the pattern of GAN image generation.


## Outputs
As of now, I have a total of 299 rounds set up for this program. Then I came up with very good results.

Here are some of the outputs of my work, and I think some of them have AI drawing sheep as well as humans do. I think it's a very lovely thing to see the AI drawing the sketches.

Epoch 71:

![71](https://github.com/zhangxiangna/coding3/raw/main/image/71.png "71")


Epoch 212:

![212](https://github.com/zhangxiangna/coding3/raw/main/image/212.png "212")

And some really bad...

![281](https://github.com/zhangxiangna/coding3/raw/main/image/281.png "281")

Finally, a motion picture demonstrating the entire process

![GIF](https://github.com/zhangxiangna/coding3/blob/main/GIF.gif "GIF")
## Summary
Unlike the previous attempts, I used only a single dataset for unsupervised learning this time. Instead of a dataset containing both training and testing sets. This was an interesting attempt for me. I think this approach is suitable for simple examples and rapid prototype development.In the future, I hope to improve the image quality of the generated images and perform as many rounds as possible to generate more realistic images.
