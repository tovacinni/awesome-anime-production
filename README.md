# Survey of Technology for Anime Production

Japanese-style animation (colloquially known as 'anime') is an art form that generally involves frames that are drawn frame-by-frame and organized using timesheets, which are time-series pointer-tables for frames. The word 'anime' in English communities have been semantically broadened to mean 'an art style that is reminiscent of popular art styles in Japanese manga / animation', but in this article we will refer to 'anime' as specifically 'animations created in a Japanese-style production flow'. 

While a large portion of the rest of the 2D animation world evolved to a rigged, _cutout_ animation style, Japanese anime productions kept the traditional frame-by-frame method of animation and have evolved in its own ways. In the midst of this, however, the adoption of technology has been relatively sparse compared to for rigged animation. This is due to a number of different reasons, but one of them is that technology that actually suits the frame-by-frame production workflow has generally been sparse.

This repository aims to curate papers, talks, and blog posts which seem promising to be used inside production workflows for anime production. Eventually the long-term goal is to create a comprehensive document / paper / course to highlight opportunities and challenges for technological development for anime production.

This is very much work in progress.

## Pre-Production

### Storyboarding

[Storeoboard: Sketching Stereoscopic Storyboards](https://dl.acm.org/doi/abs/10.1145/2858036.2858079)\
Rorik Henrikson, Bruno De Araujo, Fanny Chevalier, Karan Singh, Ravin Balakrishnan\
_CHI 2016_

[Griffith: A Storyboarding Tool Designed with Japanese Animation Professionals](https://research.archinc.jp/en/griffith/)\
Jun Kato, Kenta Hara, Nao Hirasawa\
_CHI 2024_

[CollageVis: Rapid Previsualization Tool for Indie Filmmaking using Video Collages](https://ryosuzuki.org/collagevis/)\
Hye-Young Jo, Ryo Suzuki, Yoonji Kim \
_CHI 2024_

### Script to Storyboard

[Neural Storyboard Artist: Visualizing Stories with Coherent Image Sequences](https://arxiv.org/abs/1911.10460)\
Shizhe Chen, Bei Liu, Jianlong Fu, Ruihua Song, Qin Jin, Pingping Lin, Xiaoyu Qi, Chunting Wang, Jin Zhou\
_MM 2019_

[ASAP: Auto-generating Storyboard and Previz](https://dl.acm.org/doi/abs/10.1145/3550453.3570124)\
Hanseob Kim, Ghazanfar Ali, Bin Han, Hwangyoun Kim, Jieun Kim, Jae-In Hwang\
_SIGGRAPH Asia 2022 Real-time Live!_

[Dynamic Storyboard Generation in an Engine-based Virtual Environment for Video Production](https://dl.acm.org/doi/abs/10.1145/3550453.3570124)\
Anyi Rao, Xuekun Jiang, Yuwei Guo, Linning Xu, Lei Yang, Libiao Jin, Dahua Lin, Bo Dai

## In-Betweening (Douga)

### Vector In-Betweening

[Inbetweening for computer animation utilizing moving point constraints](https://history.siggraph.org/learning/inbetweening-for-computer-animation-utilizing-moving-point-constraints-by-baecker-miller-and-reeves/)\
William Reeves\
_SIGGRAPH 1981_

[Deep Geometrized Cartoon Line Inbetweening](https://github.com/lisiyao21/AnimeInbet)\
Li Siyao, Tianpei Gu, Weiye Xiao, Henghui Ding, Ziwei Liu, Chen Change Loy\
_ICCV 2023_

[Efficient Interpolation of Rough Line Drawings](https://inria.hal.science/hal-04202841)\
Jiazhou Chen, Xinding Zhu, Melvin Even, Jean Basset, Pierre Bénard, Pascal Barla\
_Pacific Graphics 2023_

### Raster In-Betweening

[Optical Flow Based Line Drawing Frame Interpolation Using Distance Transform to Support Inbetweenings](https://ieeexplore.ieee.org/document/8803506)\
Rei Narita, Keigo Hirakawa, Kiyoharu Aizawa\
_ICIP 2019_

[Improving the Perceptual Quality of 2D Animation Interpolation](https://arxiv.org/abs/2111.12792)\
Shuhong Chen, Matthias Zwicker\
_ECCV 2022_

### Raster-to-Vector + Correspondence

[End-to-End Line Drawing Vectorization](https://ttwong12.github.io/papers/linevector/linevector.pdf)\
Hanyuan Liu, Chengze Li, Xueting Liu, Tien-Tsin Wong\
_AAAI 2022_

[Joint Stroke Tracing and Correspondence for 2D Animation](https://dl.acm.org/doi/10.1145/3649890)\
Haoran Mo, Chengying Gao, Ruomei Wang\
_Transactions on Graphics 2024_

## Colorization (Shiage)

### Colorization Systems

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

### Colorization Tools

[Area Flooding Algorithms](https://graphics.stanford.edu/papers/area-flooding-sig82course/area-flooding-sig82course.pdf)\
Marc Levoy\
_SIGGRAPH 1982 Course Notes_

[LazyBrush: Flexible Painting Tool for Hand-drawn Cartoons](https://dcgi.fel.cvut.cz/home/sykorad/lazybrush.html)\
Daniel Sykora, John Dingliana, Steven Collins\
_Eurographics 2009_\
[TV Paint Plugin](http://lazy-brush.com)

## Compositing (Satsuei)

### Raster Composition 

[Merging and Transformation of Raster Images for Cartoon Animation](https://graphics.stanford.edu/papers/merging-sig81/)\
Bruce Wallace\
_SIGGRAPH 1981_

[Compositing Digital Images](https://graphics.pixar.com/library/Compositing/)\
Thomas Porter, Tom Duff\
_SIGGRAPH 1984_\
The original 'pre-multiplied alpha' paper!

[Digital Compositing Derivations (CS 248)](https://graphics.stanford.edu/courses/cs248-01/comp/comp.html)\
Marc Levoy


## Systems

[A Color Animation System Based on the Multiplane Technique](https://graphics.stanford.edu/papers/multiplane/)\
Marc Levoy\
_SIGGRAPH 1977_

Computer Animation Production System (CAPS)\
[Proposal by Alvy Ray Smith](http://alvyray.com/DigitalLight/CAPS_Proposal_AlvyToDisney_30Jan85.pdf)\
[Executive Summary by Alvy Ray Smith](http://alvyray.com/DigitalLight/CAPS_ExecSummary_AlvyToPixar_4May86.pdf)

[Spreadsheets for Images](https://graphics.stanford.edu/papers/spreadsheets/)\
Marc Levoy\
_SIGGRAPH 1994_

[TicTacToon: A Paperless System for Professional 2D Animation](https://dl.acm.org/doi/pdf/10.1145/218380.218417)\
Jean-Daniel Fekete, Érick Bizouarn, Éric Cournarie, Thierry Galas, Frédéric Taillefer\
_SIGGRAPH 1995_

## Tools

[SmartShadow: Artistic Shadow Drawing Tool for Line Drawings](https://lllyasviel.github.io/Style2PaintsResearch/iccv2021/index.html)\
Lvmin Zhang, Jinyue Jiang, Yi Ji, Chunping Liu\
_ICCV 2021_

[Learning to Shadow Hand-drawn Sketches](https://cal.cs.umbc.edu/Papers/Zheng-2020-Shade/)\
Qingyuan Zheng, Zhuoru Li, Adam W. Bargteil\
_CVPR 2022_ 

[Sprite-from-Sprite: Cartoon Animation Decomposition with Self-supervised Sprite Estimation](https://lllyasviel.github.io/GitPageToonDecompose/)\
Lvmin Zhang, Tien-Tsin Wong, Yuxin Liu\
_SIGGRAPH Asia 2022_

[Voice Animator: Automatic Lip-Synching in Limited Animation by Audio](https://link.springer.com/chapter/10.1007/978-3-319-76270-8_12)\
Shoichi Furukawa, Tsukasa Fukusato, Shugo Yamaguchi, Shigeo Morishima

[Instance-guided Cartoon Editing with a Large-scale Dataset](https://cartoonsegmentation.github.io)\
Jian Lin, Chengze Li, Xueting Liu, Zhongping Ge

[APISR: Anime Production Inspired Real-World Anime Super-Resolution](https://arxiv.org/abs/2403.01598)\
Boyang Wang, Fengyu Yang, Xihang Yu, Chao Zhang, Hanbin Zhao

## Inspirational

[LACES: Live Authoring Through Compositing and Editing of Video Stream](http://www.cs.toronto.edu/~fchevali/fannydotnet/resources_pub/pdf/laces_chi2014.pdf)\
Dustin Freeman, Stephanie Santosa, Fanny Chevalier, Ravin Balakrishnan, Karan Singh\
_CHI 2014_

## Acknowledgements

Thanks to [Chenxi Liu](https://chenxil21.github.io) for helping to put together this list!
