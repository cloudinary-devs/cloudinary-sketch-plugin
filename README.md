
<p align="center">
<img src="https://res.cloudinary.com/mayashavin/image/upload/w_600/Screen_Shot_2019-05-27_at_11.58.32.png" />
</p>
  </p>
<h1 align="center"> Cloudinary plugin for Sketch</h1>

[![Netlify Status](https://api.netlify.com/api/v1/badges/9466625f-03ea-41d4-9500-5b35c64b3274/deploy-status)](https://app.netlify.com/sites/cloudinary-sketch-plugin/deploys)

This Sketch plugin allows designers to fetch images from [Cloudinary](https://cloudinary.com) DAM. It also allows Uploading Artboards (or layers) *directly* to Cloudinary using an Upload preset.

The images fetched will be optimized in size with [g_auto](https://cloudinary.com/documentation/image_transformations#automatic_cropping) and [q_auto](https://cloudinary.com/documentation/image_transformations#automatic_quality_and_encoding_settings).

The plugin was developed as part of the Cloudinary Hackathon (May 2019).

> ⚠️ This project is in an early stage and lacks documentation. If you're interested in contributing or using it at your company, feel free to open GitHub issues.

------
Of the functions we would offer:

## The ability to insert assets from Cloudinary’s DAM to Sketch

### Using Public ID 

<p align="center">
<img src="https://res.cloudinary.com/boazz/video/upload/c_crop,w_900,h_600,g_north_west,e_accelerate:100/e_accelerate:100/w_600,q_80,e_accelerate:100,e_loop/sketch-demo/sketch_flow_insert.gif" alt="Insert using public id" />
</p>

### Using Search
![Using Search](https://res.cloudinary.com/boazz/video/upload/c_crop,w_800,h_800,g_west,q_auto,e_accelerate:200,e_loop/w_600/sketch-demo/sketch_flow_insert-search_02.gif)

These can be done on multiple assets in parallel

## Upload artboard from Sketch to DAM

<p align="center">
<img src="https://res.cloudinary.com/boazz/video/upload/w_900,h_600,c_crop,g_north_west,q_70,e_accelerate:100/e_accelerate:400/w_600,e_loop,f_gif/sketch-demo/sketch_flow_upload.jpg" />
</p>

This can be done while using our upload preset features such as auto tagging, auto folder assignment and more.


## Installation

- [Download](../../releases/latest/download/cloudinary-plugin.sketchplugin.zip) the latest release of the plugin
- Un-zip
- Double-click on cloudinary-plugin.sketchplugin

## Development Guide

_This plugin was created using `skpm`. For a detailed explanation on how things work, checkout the [skpm Readme](https://github.com/skpm/skpm/blob/master/README.md)._

### Contributors

- Design & Development [@mayashavin](https://github.com/mayashavin)
- Development [@taragano](https://github.com/taragano)
- Product Design [@aniboaz](https://github.com/aniboaz)

## License
[MIT](LICENSE.md)
