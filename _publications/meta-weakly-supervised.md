---
title: "One-Shot Weakly Supervised Video Object Segmentation"
collection: publications
permalink: /publication/meta-weakly-supervised
date: 2019-12-18
venue: '--'
paperurl: ''
citation: 'Mennatullah Siam*, <b>Naren Doraiswamy*</b>, Boris Oreshkin*, Hengshuai Yao, Martin Jagersand. (2019).<i>Under review in ICLR 2020 Workshop</i>. <b>ICLR 2020</b>'
---
[[PDF]](https://arxiv.org/abs/1912.08936)

Conventional few-shot object segmentation methods learn object segmentation from a few labelled support images with strongly labelled segmentation masks. Recent work has shown to perform on par with weaker levels of supervision in terms of scribbles and bounding boxes. However, there has been limited attention given to the problem of few-shot object segmentation with image-level supervision. We propose a novel multi-modal interaction module for few-shot object segmentation that utilizes a co-attention mechanism using both visual and word embeddings. It enables our model to achieve 5.1% improvement over previously proposed image-level few-shot object segmentation. Our method compares relatively close to the state of the art methods that use strong supervision, while ours use the least possible supervision. We further propose a novel setup for few-shot weakly supervised video object segmentation(VOS) that relies on image-level labels for the first frame. The proposed setup uses weak annotation unlike semi-supervised VOS setting that utilizes strongly labelled segmentation masks. The setup evaluates the effectiveness of generalizing to novel classes in the VOS setting. The setup splits the VOS data into multiple folds with different categories per fold. It provides a potential setup to evaluate how few-shot object segmentation methods can benefit from additional object poses, or object interactions that is not available in static frames as in PASCAL-5i benchmark. 
