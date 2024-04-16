# Survey of Technology for Anime Production

Japanese-style animation (colloquially known as 'anime') is an art form that generally involves frames that are drawn frame-by-frame and organized using timesheets, which are time-series pointer-tables for frames. The word 'anime' in English communities have been semantically broadened to mean 'an art style that is reminiscent of popular art styles in Japanese manga / animation', but in this article we will refer to 'anime' as specifically 'animations created in a Japanese-style production flow'. 

While a large portion of the rest of the 2D animation world evolved to a rigged, _cutout_ animation style, Japanese anime productions kept the traditional frame-by-frame method of animation and have evolved in its own ways. In the midst of this, however, the adoption of technology has been relatively sparse compared to for rigged animation. This is due to a number of different reasons, but one of them is that technology that actually suits the frame-by-frame production workflow has generally been sparse.

This repository aims to curate papers, talks, and blog posts which seem promising to be used inside production workflows for anime production. Eventually the long-term goal is to create a comprehensive document / paper / course to highlight opportunities and challenges for technological development for anime production.

This is very much work in progress.

## Pre-Production

[Griffith: A Storyboarding Tool Designed with Japanese Animation Professionals](https://research.archinc.jp/en/griffith/)\
Jun Kato, Kenta Hara, Nao Hirasawa\
_CHI 2024_

## In-Betweening (Douga)

[Inbetweening for computer animation utilizing moving point constraints](https://history.siggraph.org/learning/inbetweening-for-computer-animation-utilizing-moving-point-constraints-by-baecker-miller-and-reeves/)\
William Reeves\
_SIGGRAPH 1981_

[Optical Flow Based Line Drawing Frame Interpolation Using Distance Transform to Support Inbetweenings](https://ieeexplore.ieee.org/document/8803506)\
Rei Narita, Keigo Hirakawa, Kiyoharu Aizawa\
_ICIP 2019_

[Improving the Perceptual Quality of 2D Animation Interpolation](https://arxiv.org/abs/2111.12792)\
Shuhong Chen, Matthias Zwicker\
_ECCV 2022_

[Deep Geometrized Cartoon Line Inbetweening](https://github.com/lisiyao21/AnimeInbet)\
Li Siyao, Tianpei Gu, Weiye Xiao, Henghui Ding, Ziwei Liu, Chen Change Loy\
_ICCV 2023_

[Efficient Interpolation of Rough Line Drawings](https://inria.hal.science/hal-04202841)\
Jiazhou Chen, Xinding Zhu, Melvin Even, Jean Basset, Pierre Bénard, Pascal Barla\
_Pacific Graphics 2023_

[Joint Stroke Tracing and Correspondence for 2D Animation](https://dl.acm.org/doi/10.1145/3649890)\
Haoran Mo, Chengying Gao, Ruomei Wang\
_Transactions on Graphics 2024_

## Colorization (Shiage)

[Graph Matching based Anime Colorization with Multiple References](https://dl.acm.org/doi/abs/10.1145/3306214.3338560)\
Akinobu Maejima, Hiroyuki Kubo, Takuya Funatomi, Tatsuo Yotsukura, Satoshi Nakamura, Yasuhiro Mukaigawa\
_SIGGRAPH Posters 2019_

[Anime Character Colorization using Few-shot Learning](https://dl.acm.org/doi/10.1145/3478512.3488604)\
Akinobu Maejima, Hiroyuki Kubo, Seitaro Shinagawa, Takuya Funatomi, Tatsuo Yotsukura, Satoshi Nakamura, Yasuhiro Mukaigawa\
_SIGGRAPH Asia Technical Communications 2021_

[Improved Automatic Colorization by Optimal Pre-colorization](https://dl.acm.org/doi/abs/10.1145/3588028.3603669)\
Taiki Watanabe, Seitaro Shinagawa, Takuya Funatomi, Akinobu Maejima, Yasuhiro Mukaigawa, Satoshi Nakamura, Hiroyuki Kubo\
_SIGGRAPH Posters 2023_

[Learning Inclusion Matching for Animation Paint Bucket Colorization](https://github.com/ykdai/BasicPBC)\
Yuekun Dai, Shangchen Zhou, Qinyue Li, Chongyi Li, Chen Change Loy\
_CVPR 2024_

[Deep Line Art Video Colorization with a Few References](https://arxiv.org/abs/2003.10685)\
Min Shi, Jia-Qi Zhang, Shu-Yu Chen, Lin Gao, Yu-Kun Lai, Fang-Lue Zhang

[Coloring Anime Line Art Videos with Transformation Region Enhancement Network
](https://dl.acm.org/doi/abs/10.1016/j.patcog.2023.109562)\
Ning Wang, Muyao Niu, Zhi Dou, Zhihui Wang, Zhiyong Wang, Zhaoyan Ming, B. Liu, Hao Li

## Post-Processing / Tools

[Merging and Transformation of Raster Images for Cartoon Animation](https://graphics.stanford.edu/papers/merging-sig81/)\
Bruce Wallace\
_SIGGRAPH 1981_

[Voice Animator: Automatic Lip-Synching in Limited Animation by Audio](https://link.springer.com/chapter/10.1007/978-3-319-76270-8_12)\
Shoichi Furukawa, Tsukasa Fukusato, Shugo Yamaguchi, and Shigeo Morishima

[Instance-guided Cartoon Editing with a Large-scale Dataset](https://cartoonsegmentation.github.io)\
Jian Lin, Chengze Li, Xueting Liu, Zhongping Ge

[APISR: Anime Production Inspired Real-World Anime Super-Resolution](https://arxiv.org/abs/2403.01598)\
Boyang Wang, Fengyu Yang, Xihang Yu, Chao Zhang, Hanbin Zhao

## Systems

[A Color Animation System Based on the Multiplane Technique](https://graphics.stanford.edu/papers/multiplane/)\
Marc Levoy\
_SIGGRAPH 1977_

Computer Animation Production System (CAPS)\
[Proposal by Alvy Ray Smith](http://alvyray.com/DigitalLight/CAPS_Proposal_AlvyToDisney_30Jan85.pdf)\
[Executive Summary by Alvy Ray Smith](http://alvyray.com/DigitalLight/CAPS_ExecSummary_AlvyToPixar_4May86.pdf)


