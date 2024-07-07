#### S3C-CT | CAAI Trans. Intell. Tech. 2023 | HSI Change Detection
---
## Spectral-Spatial Sequence Characteristics-Based Convolutional Transformer for Hyperspectral Change Detection

***Chengle Zhou, Qian Shi, Da He, Bing Tu, Haoyang Li, and Antonio Plaza***

*CAAI Transactions on Intelligence Technology, vol. 8, no. 4, pp. 1237-1257, Dec. 2023*

---

![framework](https://github.com/chengle-zhou/MY-IMAGE/blob/4a652946efb8aa6fd108c6790f26a40d398ae0d4/S3C-CT/framework.png)

Fig. 1. Overview of the proposed S3C-CT method for hyperspectral change detection.



## Abstract

Recently, ground coverings change detection (CD) driven by bitemporal hyperspectral images (HSIs) has become a hot topic in the remote sensing community. There are two challenges in the HSI-CD task: (1) attribute feature representation of pixel pairs and (2) feature extraction of attribute patterns of pixel pairs. To solve the above problems, a novel spectral-spatial sequence characteristics-based convolutional transformer (S3C-CT) method is proposed for the HSI-CD task. In the designed method, firstly, an eigenvalue extrema-based band selection strategy is introduced to pick up spectral information with salient attribute patterns. Then, a 3D tensor with spectral-spatial sequence characteristics is proposed to represent the attribute features of pixel pairs in the bitemporal HSIs. Next, a fusion framework of the convolutional neural network (CNN) and Transformer encoder (TE) is designed to extract high-order sequence semantic features, taking into account both local context information and global sequence dependencies. Specifically, a spatial-spectral attention mechanism is employed to prevent information reduction and enhance dimensional interactivity between the CNN and TE. Finally, the binary change map is determined according to the fully-connected layer. Experimental results on real HSI datasets indicated that the proposed S3C-CT method outperforms other well-known and state-of-the-art detection approaches in terms of detection performance.

## Results
Change detection results (%) of various methods on the River dataset when training with 3600 weak-samples (changed: 1200 and unchanged: 2400). (a) Reference data, (b) Weak training samples, (c) CAV (OA = 88.51%), (d) MMPs (OA = 92.392%), (e) SALA (OA = 91.46%), (f) SVM (OA = 94.86%), (g) 2DCNN (OA = 93.87%), (h) DSFA (OA = 89.80%), (i) GETNET (OA = 93.27%), (j) SFBS (OA = 95.35%), (k) ViT (OA = 90.757%), and (l) the proposed S3C-CT method (OA = 96.29%).
![result1](https://github.com/chengle-zhou/MY-IMAGE/blob/4a652946efb8aa6fd108c6790f26a40d398ae0d4/S3C-CT/result1.png)

Change detection accuracy obtained for the river hyperspectral dataset by the CVA, MMPs, SALA, SVM, 2DCNN, DSFA, GETNET, SFBS, ViT, and the proposed S3C-CT methods.
![table1](https://github.com/chengle-zhou/MY-IMAGE/blob/4a652946efb8aa6fd108c6790f26a40d398ae0d4/S3C-CT/table1.png)



In preparation for release soon.

Please cite our new paper:

**Plain Text:**

Chengle Zhou, Qian Shi, Da He, Bing Tu, Haoyang Li, and Antonio Plaza. "[Spectral-Spatial Sequence Characteristics-Based Convolutional Transformer for Hyperspectral Change Detection](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cit2.12226)." CAAI Transactions on Intelligence Technology. 2023 Dec, 8(4):1237-1257.

**BibTex:**

```latex
@article{Zhou2023HSICD,
  title = {Spectral‐spatial sequence characteristics‐based convolutional transformer for hyperspectral change detection},
  volume = {8},
  ISSN = {2468-2322},
  url = {http://dx.doi.org/10.1049/cit2.12226},
  DOI = {10.1049/cit2.12226},
  number = {4},
  journal = {CAAI Transactions on Intelligence Technology},
  publisher = {Institution of Engineering and Technology (IET)},
  author = {Zhou, Chengle and Shi, Qian and He, Da and Tu, Bing and Li, Haoyang and Plaza, Antonio},
  year = {2023},
  month = may,
  pages = {1237–1257}
}
```
