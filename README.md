<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250"/> <br>
  
<img src="poster"/>

<p align="center">

  <a href="#overview">Overview</a> •
  <a href="#download">Download</a> •
  <a href="#example">Example</a> •
  <a href="#license">License</a>
  
</p>

<!-- [![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervise.ly/slack) 
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/aerial-power-infrastructure-detection-train-dataset)
[![views](https://app.supervise.ly/img/badges/views/supervisely-ecosystem/aerial-power-infrastructure-detection-train-dataset.png)](https://supervise.ly)
[![downloads](https://app.supervise.ly/img/badges/downloads/supervisely-ecosystem/aerial-power-infrastructure-detection-train-dataset.png)](https://supervise.ly) -->

# Cracks Synthetic Dataset

</div>

# Overview

### Dataset contains:
- 1158 synthetic images with Ground Truth *(target domain)*
- 400 synthetic images with Ground Truth with Style Transfer Augmentation *(target domain)*
- 628 real images **without** Ground Truth *(source domain)*
- 70 real images with Ground Truth for **Validation** *(source domain)*

<img src="folder overveiw"/> 


### How the data was generated

We have collected about 200 real photos (or textures) of asphalt, wall, concrete and other images of various materials that are used as a background. Then we overlaid these textures with procedurally generated cracks. To embed the cracks in the texture and make it more realistic, we apply some post-processing algorithm. Also, there is a subset of 400 images which were obtained by applying a Style Transfer model to increase the variety of the data.

# Download
Direct download: [tar archive]() (??? MB)

# Example

<img src="examples"/>
> Examples of images labeled with three classes of objects: insulator, pollution flashover, broken.

# License

...