# Learning Transformers right from the Beginning

- [Learning Transformers right from the Beginning](#learning-transformers-right-from-the-beginning)
  - [NLP](#nlp)
  - [Vision Transformers](#vision-transformers)
  - [Video Transformers](#video-transformers)

## NLP

Start with [The illustrated Transformer](https://jalammar.github.io/illustrated-transformer/).
It is the most comprehensible guide to start with visual aid.

For deeper level understanding:

* [The original paper from 2017](http://nlp.seas.harvard.edu/2018/04/03/attention.html).

* [The annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html) comments the code implementation.

* [The illustrated BERT](https://jalammar.github.io/illustrated-bert/), a pretty popular model 
which is now the base for new models that are coming around, and its [paper (2018)](https://arxiv.org/abs/1810.04805). 

* [Hugging Face library that encapsules a lot of transformer models for you to choose :)](https://huggingface.co/docs/transformers/index).



## Vision Transformers

* [The original Vision Transformer](https://arxiv.org/abs/2010.11929) and its [github](https://arxiv.org/abs/2010.11929).
It is easier to use the [hugging face library ViT though](https://huggingface.co/docs/transformers/model_doc/vit).

* The next gen ViT that is a backbone to most Vision tasks, [The Swin Transformer](https://arxiv.org/abs/2103.14030),
and its second version, [Swin V2](https://arxiv.org/abs/2111.09883). 
The second version had some tweaks so as to be more scalable and use images with high-resolution.
They also pre-trained Swin V2 in a self-supervised way.
Both models are available at huggingface through the pages: [Swin V1](https://huggingface.co/docs/transformers/v4.26.0/en/model_doc/swin#overview) and [Swin V2](https://huggingface.co/docs/transformers/v4.26.0/en/model_doc/swinv2). 
 
* Another model that seems to be excellent is [BEIT](https://arxiv.org/abs/2106.08254) which is based on BERT. This is also available at [huggingface](https://huggingface.co/docs/transformers/model_doc/beit). 
 
## Video Transformers

Now the ultimate level, the one that will test your limits and understanding of the previous models.
The Video transformer. I will confess that I am new to this Video Transformer thing, but here come
some suggestions. I personally just read about the Video Swin Transformer.

* [Video Swin Transformer](https://arxiv.org/abs/2106.13230). The code is in the same repository as Swin V1 and V2.
There is an implementation of this model on [torchvision lib](https://pytorch.org/vision/main/models/video_swin_transformer.html).

The ones that I do not know but want to know more about:

* Hugging face implementation of [TimeSFormer](https://huggingface.co/docs/transformers/v4.26.0/en/model_doc/timesformer#transformers.TimesformerForVideoClassification).

* Torchvision implementation of [MVIT](https://pytorch.org/vision/stable/models/video_mvit.html)
another video transformer for classification and detection.

* Another interesting model is [Swin2SR](https://pytorch.org/vision/main/models/video_swin_transformer.html)
which performs Super Resolution tasks on compressed image and videos.