# Text to Video


Latest Model -:

1. MetaAi(by Meta)
2. Imagen Video(by google)
3. Phenaki(by google)


## MetaAi 
Make-A-Video research builds on the recent progress made in text-to-image generation technology built to enable text-to-video generation. The system uses images with descriptions to learn what the world looks like and how it is often described. It also uses unlabeled videos to learn how the world moves. With this data, Make-A-Video lets you bring your imagination to life by generating whimsical, one-of-a-kind videos with just a few words or lines of text.

[Research paper](https://arxiv.org/pdf/2209.14792.pdf)

[website](https://makeavideo.studio/)


DataSet Used by the Meta to train the model

1. [Laion-5b](https://laion.ai/blog/laion-5b/) a dataset of 5,85 billion CLIP-filtered image-text pairs, 14x bigger than LAION-400M, previously the biggest openly accessible image-text dataset in the world.

2. [WebVid-10M](https://m-bain.github.io/webvid-dataset/) is a large-scale dataset of short videos with textual descriptions sourced from stock footage sites. The videos are diverse and rich in their content.

    10.7M video-caption pairs.

    52K total video hours.
3. [HD-VILA-100M](https://github.com/microsoft/XPretrain/tree/main/hd-vila-100m) HD-VILA-100M is a large-scale, high-resolution, and diversified video-language dataset to facilitate the multimodal representation learning.

4. [NSFW Detection Machine Learning Model](https://github.com/GantMan/nsfw_model) filter out sample pairs with NSFW images 2,toxic words in the text,or images with a watermark probability 


## ImagenVideo

Imagen Video builds on Google’s Imagen, an image-generating system comparable to OpenAI’s DALL-E 2 and Stable Diffusion. Imagen is what’s known as a “diffusion” model, generating new data (e.g. videos) by learning how to “destroy” and “recover” many existing samples of data. As it’s fed the existing samples, the model gets better at recovering the data it’d previously destroyed to create new works.

[Research paper](https://imagen.research.google/video/paper.pdf)

[website](https://imagen.research.google/video/)

dataset used by imagen(google)-:
a combination of an internal dataset consisting of 14 million video-text pairs
and 60 million image-text pairs, and the publicly available LAION-400M image-text dataset.

they didnt provided any link related to data othere tahna laion dataset

## Phenaki
An AI model called Phenaki can generate minutes of coherent video based on detailed, sequential text input.
While Imagen Video focuses on quality, Phenaki prioritizes coherency and length. The system can turn paragraph-long prompts into films of an arbitrary length,

[Research Paper](https://openreview.net/forum?id=vOEXS39nOF)

[Website](https://phenaki.video/)



dataset used by imagen(Phenaki)-:
1. [Moment in time (MIT) Dataset](http://moments.csail.mit.edu/)



# Cog-Video
production of text-to-video, transformation of 9 billion parameters, and inheritance of a trained text-to-image model One of the first large-scale pretrained open-source text-to-video models, CogView2 has a multi-frame-rate hierarchical training technique and outperforms all currently available models.

[Research paper](https://arxiv.org/pdf/2205.15868.pdf)

[Website](https://github.com/THUDM/CogVideo)





