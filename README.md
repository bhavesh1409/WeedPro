# WeedPro: Segmentation and Classification of Weeds and Crop in Smart Farming

## Overview

WeedPro is a precision agriculture project aimed at revolutionizing weed management in onion fields using cutting-edge machine vision and deep learning techniques. It offers an automated and efficient solution to identify and control weeds, thus optimizing the use of resources and promoting sustainable farming practices.

<img width="1366" alt="Screenshot 2023-07-29 at 6 03 20 PM" src="https://github.com/bhavesh1409/WeedPro/assets/107453233/647df099-efa8-433c-8b8c-fa5ba57e4c9d">



## Goal of WeedPro

The primary goal of WeedPro is to develop a robust and accurate weed management system for onion fields that reduces the dependency on chemical weedicides. By leveraging machine vision and deep learning, WeedPro seeks to achieve the following objectives:

- *Precise Weed Detection*: Accurately identify and classify different weed species present in onion fields, enabling targeted and effective weed control measures.

- *Optimized Spray Point Localization*: Determine the optimal spray points on the identified weeds to minimize weedicide usage while ensuring effective weed suppression.

- *Enhanced Crop Yield*: Improve the overall onion crop yield by efficiently managing weeds and reducing competition for resources.

## Methodology and Approach
<img width="1378" alt="Screenshot 2023-07-29 at 6 05 24 PM" src="https://github.com/bhavesh1409/WeedPro/assets/107453233/ca854961-476a-4fb3-b1f4-5acdadbe8a0d">


WeedPro employs a sophisticated methodology that combines binary segmentation and multi-class segmentation techniques along with object detection for precise spray point localization. The key components of the approach are as follows:

1. *Binary Segmentation for ROI*: Implement a reduced binary segmentation model to extract the Region of Interest (ROI) from the onion field images. This step focuses on identifying weed areas in the images.

2. *Multi-Class Segmentation*: Design a modified U-Net architecture to perform multi-class segmentation of the extracted ROI. The model categorizes the identified weeds into different classes based on their species.

3. *Object Detection for Spray Point Localization*: Develop a methodology to precisely localize the optimal spray points on the identified weeds. This ensures accurate application of weedicide only where required, minimizing environmental impact.

<img width="442" alt="Screenshot 2023-07-29 at 6 11 55 PM" src="https://github.com/bhavesh1409/WeedPro/assets/107453233/f29448f6-3b57-4589-a8ee-525b7ede2014">


The above images shows the intermediate results generated before passing the image to Objection detection model for spray point localization.

## Dataset

The WeedPro project utilizes a meticulously curated dataset of 800 images collected from IGKV, Raipur, featuring onion crops and various weed species. Each image is manually annotated to provide ground truth data for training and evaluation.

<img width="355" alt="Screenshot 2023-07-29 at 6 17 56 PM" src="https://github.com/bhavesh1409/WeedPro/assets/107453233/d3c1dff9-935d-485f-b4e8-cbae6c1dba87">
