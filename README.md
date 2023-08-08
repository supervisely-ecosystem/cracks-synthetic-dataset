<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250"/> <br>
<img src="https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/assets/115161827/dc1093a4-730f-4d35-aac5-5836deadeea6"/>

# Cracks Synthetic Dataset

<p align="center">

  <a href="#overview">Overview</a> •
  <a href="#download">Download</a> •
  <a href="#samples">Samples</a> •
  <a href="#license">License</a>
  
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervise.ly/slack) 
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/cracks-synthetic-dataset)
[![views](https://app.supervise.ly/img/badges/views/supervisely-ecosystem/cracks-synthetic-dataset.png)](https://supervise.ly)
[![downloads](https://app.supervise.ly/img/badges/downloads/supervisely-ecosystem/cracks-synthetic-dataset.png)](https://supervise.ly)


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
Direct download links (286 MB):
- [zip](https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/archive/refs/heads/master.zip)
- [tar.gz](https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/archive/refs/heads/master.tar.gz)

# Samples

| source_synthetic | source_synthetic_styled | target_unlabeled | validation |
| ---------------- | ----------------------- | ---------------- | ---------- |
| <img src="https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/assets/119248312/cd4e9548-3fa1-45a9-bb5f-12d9a04e85d7" width=150px /> | <img src="https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/assets/119248312/c1c21d33-d4cc-45d6-bb2f-acb5dd3cb541" width=150px /> | <img src="https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/assets/119248312/11dedeb6-38b5-49d3-887a-93c54a9cbdb4" height=150px /> | <img src="https://github.com/supervisely-ecosystem/cracks-synthetic-dataset/assets/119248312/973d7bdf-9463-4d30-83a3-f86006405326" height=150px /> |

# License

License: Creative Commons Attribution 4.0 International (CC BY 4.0)

If you use this dataset, cite us:
```
@misc{ Computer Vision Dataset,
    title = { Cracks Synthetic Dataset },
    type = { Open Source Dataset },
    author = { Supervisely },
    howpublished = { \url{ https://ecosystem.supervisely.com/projects/cracks-synthetic-dataset } },
    url = { https://ecosystem.supervisely.com/projects/cracks-synthetic-dataset },
    journal = { Supervisely Ecosystem },
    publisher = { Supervisely },
    year = { 2023 },
    month = { aug },
}
```
