<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250"/> <br>
  
TODO: poster
<img src="poster"/>

<p align="center">

  <a href="#overview">Overview</a> •
  <a href="#download">Download</a> •
  <a href="#samples">Samples</a> •
  <a href="#license">License</a>
  
</p>

TODO: shields
<!-- [![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervise.ly/slack) 
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/aerial-power-infrastructure-detection-train-dataset)
[![views](https://app.supervise.ly/img/badges/views/supervisely-ecosystem/aerial-power-infrastructure-detection-train-dataset.png)](https://supervise.ly)
[![downloads](https://app.supervise.ly/img/badges/downloads/supervisely-ecosystem/aerial-power-infrastructure-detection-train-dataset.png)](https://supervise.ly) -->

# Cracks Synthetic Dataset

</div>

# Overview

### Dataset contains:
- 1158 synthetic images with Ground Truth *(source_synthetic)*
- 400 synthetic images with Ground Truth with Style Transfer Augmentation *(source_synthetic_styled)*
- 628 real images **without** Ground Truth *(target_unlabeled)*
- 70 real images with Ground Truth for **Validation** *(validation)*

### Project structure:
<img src="https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/assets/31512713/f4247c00-08ad-4b81-a5ca-fa80fb64da1c" width="75%"/>


### How the data was generated

We have collected about 200 real photos (or textures) of asphalt, wall, concrete and other images of various materials that are used as a background. Then we overlaid these textures with procedurally generated cracks. To embed the cracks in the texture and make it more realistic, we apply some post-processing algorithm. Also, there is a subset of 400 images which were obtained by applying [Style Transfer](https://arxiv.org/abs/2003.07694) model to increase the variety of the data.

# Download
Direct download links:
- [zip](https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/archive/refs/tags/v0.0.2.zip)
- [tar.gz](https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/archive/refs/tags/v0.0.2.tar.gz)

# Samples

| source_synthetic | source_synthetic_styled | target_unlabeled | validation |
| ---------------- | ----------------------- | ---------------- | ---------- |
| ![source_synthetic](project/source_synthetic/img/00_00006_pexels_3616764.jpg) | ![source_synthetic_styled](project/source_synthetic_styled/img/00_00_00050_pexels_1903409.jpg) | ![target_unlabeled](project/target_unlabeled/img/20220819_130424.jpg) | ![validation](project/validation/img/20220821_200938_lRGRYLlPw6.jpg) |

# License

TODO: License