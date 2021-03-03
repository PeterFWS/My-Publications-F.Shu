## [1] PlaneSegNet: Fast and Robust Plane Estimation Using a Single-stage Instance Segmentation CNN

Authors: Yaxu Xie, Jason Rambach, **Fangwen Shu**, Didier Stricker

DFKI - German Research Center for Artificial Intelligence

Paper is accepted to **IEEE ICRA 2021** (http://www.icra2021.org/)

Preprint is coming soon.

### Abstract:
Instance segmentation of planar regions in indoor scenes benefits visual SLAM and other applications such as augmented reality (AR) where scene understanding is required. Existing methods built upon two-stage frameworks show satisfactory accuracy but are limited by low frame rates. In this work, we propose a real-time deep neural architecture that estimates piece-wise planar regions from a single RGB image. Our model employs a variant of a fast single-stage CNN architecture to segment plane instances. Considering the particularity of the target detected, we propose Fast Feature Non-maximum Suppression (FF-NMS) to reduce the suppression errors resulting by overlapping bounding boxes of planes. We also utilize a Residual Feature Augmentation module in the Feature Pyramid Network (FPN). Our method achieves significantly higher frame-rates and comparable segmentation accuracy against two-stage methods. We automatically label over 70,000 images as ground truth from the Stanford 2D-3D-Semantics dataset. Moreover, we incorporate our method with a state-of-the-art planar SLAM and validate its benefits.

## [2] SLAM in the Field: An Evaluation of Monocular Mapping and Localization on Challenging Dynamic Agricultural Environment

Authors: **Fangwen Shu**, Paul Lesur, Yaxu Xie, Alain Pagani, Didier Stricker

DFKI - German Research Center for Artificial Intelligence

Paper is accepted to **IEEE/CVF WACV 2021** (http://wacv2021.thecvf.com/)

Conference version please see CVF Open Access: https://openaccess.thecvf.com/content/WACV2021/papers/Shu_SLAM_in_the_Field_An_Evaluation_of_Monocular_Mapping_and_WACV_2021_paper.pdf

Supplementary Material: https://openaccess.thecvf.com/content/WACV2021/supplemental/Shu_SLAM_in_the_WACV_2021_supplemental.pdf

### Abstract:
This paper demonstrates a system capable of combining a sparse, indirect, monocular visual SLAM, with both of-fline and real-time Multi-View Stereo (MVS) reconstruction algorithms. This combination overcomes many obstacles encountered by autonomous vehicles or robots employed in agricultural environments, such as overly repetitive patterns , need for very detailed reconstructions, and abrupt movements caused by uneven roads. Furthermore, the use of a monocular SLAM makes our system much easier to integrate with an existing device, as we do not rely on a LiDAR (which is expensive and power consuming), or stereo camera (whose calibration is sensitive to external perturbation e.g. camera being displaced). To the best of our knowledge, this paper presents the first evaluation results for monocular SLAM, and our work further explores unsupervised depth estimation on this specific application scenario by simulating RGB-D SLAM to tackle the scale ambiguity, and shows our approach produces reconstructions that are helpful to various agricultural tasks. Moreover, we highlight that our experiments provide meaningful insight to improve monocular SLAM systems under agricultural settings.

### Bibtex

```
@inproceedings{shu2021slam,
  title={SLAM in the Field: An Evaluation of Monocular Mapping and Localization on Challenging Dynamic Agricultural Environment},
  author={Shu, Fangwen and Lesur, Paul and Xie, Yaxu and Pagani, Alain and Stricker, Didier},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={1761--1771},
  year={2021}
}
```
