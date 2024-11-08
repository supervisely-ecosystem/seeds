<div align="center" markdown>
<img src="https://i.imgur.com/UdBujFN.png" width="250"/>

# Seeds

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#overview">Statistics</a> •
  <a href="#data-rights">Examples</a> • 
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervisely.com/slack) 
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/seeds)
[![views](https://app.supervisely.com/img/badges/views/supervisely-ecosystem/seeds.png)](https://supervisely.com)
[![downloads](https://app.supervisely.com/img/badges/downloads/supervisely-ecosystem/seeds.png)](https://supervisely.com)

</div>


## Overview 

<img src="https://i.imgur.com/DmHVwXj.png"/>

Demo project with seeds photos for research. Can be used as a playground for:
- testing different models: detection / segmentation / instance segmentation
- demo for synthetic data
- all images have the same resolution: 4032 * 2268 => so it is a good test for sliding window approaches
- modeling some close tasks from different industries, images may have similar properties in terms of lighting conditions, number of objects and their sizes, camera positions, etc; for example:
  - agriculture (find plants diseases, count items, inspect their properties (e.g. size) and quality)
  - medicine (x-ray)
  - microbiology (microscope images)
  - visual inspection and quality control in production (defects, holes, production lanes)
  - and so on ...

Here are some examples:
<img src="https://i.imgur.com/LAiO4Fi.png"/>

## Data Statistics

- All images have the same resolution 4032 x 2268 x 3 (height x width x channels)
  
- There are no labeled objects

- Datasets:
    - `01_background` - background images without objects
    - `02_sunflower` - sunflower seeds with different density
    - `03_pumpkin_peeled` - peeled pumpkin seeds with different density
    - `04_pumpkin_unpeeled` - unpeeled pumpkin seeds with different density
    - `05_pumpkin_mx` - mix of peeled and unpeeled pumpkin seeds with different density
    - `06_mix` - mix of sunflower, peeled and unpeeled pumpkin seeds
    
<img src="https://i.imgur.com/q0sCLsl.png" width="450px"/>
  
- Classes

<img src="https://i.imgur.com/U3TYZPw.png" width="350px"/>
