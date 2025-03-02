# Awesome-Panoptic-Segmentation
This repo is a collection of the challenging panoptic segmentation, including papers, codes, and tutorials.

## What is Panoptic Segmentation?

Summarize in one sentence : Panoptic Segmentation proposes to solve the semantic segmentation(*Stuff*) and instance segmentation(*Thing*) in a unified and general manner.

<div align="center" width="200" height="100"><img src="Selection_066.png"></div>
 
## Datasets

Generally, the datasets which contains both semantic and instance annotations can be used to solve the challenging *panoptic* task;  
* [Cityscapes](https://www.cityscapes-dataset.com/)
* [Mapillary Vistas](https://blog.mapillary.com/product/2017/05/03/mapillary-vistas-dataset.html)
* [ADE20K](http://groups.csail.mit.edu/vision/datasets/ADE20K/)
* [COCO-Panoptic](http://cocodataset.org/)
* [BDD100K](https://bair.berkeley.edu/blog/2018/05/30/bdd/) (the instance annotations are temporaily not released)

## Evaluation Metrics
* **PQ**(*Panoptic Quality*)
<div align="center" width="200" height="100"><img src="Selection_097.png"></div>

* **SQ & RQ**(*Segmentation Quality and Recognition Quality*)
<div align="center" width="200" height="100"><img src="Selection_098.png"></div>

## SOTA Results & Leaderboards
* **Mapillary Panoptic**
* **COCO Panoptic** 

| - | PQ | SQ | RQ | PQ_{Th} | SQ_{Th} | RQ_{Th} | PQ_{St} | SQ_{St} | RQ_{St} | E2E | 
| ------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | -- | 
| Megvii(Face++) | 0.532 | 0.830 | 0.632 | 0.621 | 0.852 | 0.726 | 0.398 | 0.797 | 0.489 | False |
| Panoptic FPN | 0.409 |  |  | 0.483 |  |  | 0.297 |  |  | True |

* **Cityscapes Panoptic**


## Blogs
1.**Face++ Detection Team on Panoptic Segmentation**
* Blog : https://zhuanlan.zhihu.com/p/59141570

## Papers & Codes
1.**Panoptic Segmentation**
* Paper : https://arxiv.org/abs/1801.00868

2.**Learning to Fuse Things and Stuff (CVPR2019)**
* Paper : https://arxiv.org/abs/1812.01192

3.**Panoptic Segmentation with a Joint Semantic and Instance Segmentation Network**
* Paper : https://arxiv.org/abs/1809.02110

4.**Attention-guided Unified Network for Panoptic Segmentation (CVPR2019)**
* Paper : https://arxiv.org/abs/1812.03904
* Code : Will released

5.**Weakly- and Semi-Supervised Panoptic Segmentation (ECCV2018)**
* Paper : https://arxiv.org/abs/1808.03575
* Code : https://github.com/qizhuli/Weakly-Supervised-Panoptic-Segmentation

6.**Interactive Full Image Segmentation**
* Paper : https://arxiv.org/abs/1812.01888

7.**Panoptic Feature Pyramid Networks (CVPR2019)**
* Paper : https://arxiv.org/abs/1901.02446

8.**UPSNet: A Unified Panoptic Segmentation Network**
* Paper : https://arxiv.org/abs/1901.03784

9.**Single Network Panoptic Segmentation for Street Scene Understanding**
* Paper : https://arxiv.org/abs/1902.02678

10.**DeeperLab: Single-Shot Image Parser (CVPR2019)**
* Paper : https://arxiv.org/abs/1902.05093

11 **An End-to-End Network for Panoptic Segmentation (CVPR2019)**
* Paper : https://arxiv.org/abs/1903.05027
* Code : Will released
