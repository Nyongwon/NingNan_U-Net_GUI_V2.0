# NingNan_U-Net_GUI_V2.0
# 宁南语义分割可视化工具 V2.0 使用说明  
# Ningshan Semantic Segmentation Visualization Tool V2.0 User Manual

## 目录  
## Table of Contents

1. [简介](#简介)  
1. [Introduction](#Introduction)
2. [运行环境](#运行环境)  
2. [System Requirements](#System-Requirements)
3. [工具概述](#工具概述)  
3. [Tool Overview](#Tool-Overview)
4. [使用方法](#使用方法)  
4. [Usage Instructions](#Usage-Instructions)
   - 4.1 [主页面](#主页面)  
   - 4.1 [Main Page](#Main-Page)
   - 4.2 [影像分割](#影像分割)  
   - 4.2 [Image Segmentation](#Image-Segmentation)
   - 4.3 [自定义选取制作样本](#自定义选取制作样本)  
   - 4.3 [Custom Sample Selection](#Custom-Sample-Selection)
   - 4.4 [制作标签](#制作标签)  
   - 4.4 [Label Creation](#Label-Creation)
   - 4.5 [数据增强与训练](#数据增强与训练)  
   - 4.5 [Data Augmentation and Training](#Data-Augmentation-and-Training)
5. [功能特点](#功能特点)  
5. [Features](#Features)
6. [未来发展方向](#未来发展方向)  
6. [Future Plans](#Future-Plans)
7. [结语](#结语)  
7. [Conclusion](#Conclusion)

## 简介  
## Introduction

宁南语义分割可视化工具 V2.0 是一款针对地理信息系统（GIS）和深度学习领域的实用软件，旨在简化用户在进行图像语义分割实验时的操作流程。  
Ningshan Semantic Segmentation Visualization Tool V2.0 is a practical software aimed at simplifying the operational workflow for users conducting image semantic segmentation experiments in the fields of Geographic Information Systems (GIS) and deep learning.

### 编写目的  
### Purpose of Writing

随着深度学习技术的发展，语义分割在遥感影像分析、地理信息处理等领域的应用越来越广泛。  
With the advancement of deep learning technologies, semantic segmentation is increasingly applied in remote sensing image analysis, geographic information processing, and other fields.

然而，许多用户在进行实验时常常需要频繁修改代码，导致效率低下。  
However, many users often need to frequently modify code during experiments, leading to inefficiency.

为了解决这一问题，本工具提供了一个可视化操作界面，使得用户可以通过简单的点击和拖动完成复杂的深度学习实验。  
To address this issue, this tool provides a visual operational interface allowing users to easily complete complex deep learning experiments through simple clicks and drags.

### 使用对象  
### Target Users

本工具适用于学生、科研工作者以及任何对语义分割感兴趣的用户，尤其是那些希望简化操作流程的人。  
This tool is suitable for students, researchers, and anyone interested in semantic segmentation, especially those looking to simplify their operational processes.

## 运行环境  
## System Requirements

为了确保软件的顺利运行，建议使用以下配置：  
To ensure the smooth operation of the software, the following configurations are recommended:

### 硬件要求  
### Hardware Requirements

| 类别         | 基本要求                 |  
| ------------ | ------------------------ |  
| 客户端       | 存储：100GB及以上       |  
|              | 内存：16GB及以上        |  
|              | 处理器：I5 10代及以上   |  
|              | 独立显卡：3060及以上（可缺） |  

### 软件要求  
### Software Requirements

| 类别         | 名称                      |  
| ------------ | ------------------------- |  
| 客户端       | 操作系统：Windows10及以上、Ubuntu20.4及以上 |  

## 工具概述  
## Tool Overview

### 功能一览  
### Feature Overview

该工具的主页面包含18个按钮，每个按钮对应不同的功能。  
The main page of the tool contains 18 buttons, each corresponding to different functionalities. 

用户可以根据需要选择相应功能，逐步进行实验。  
Users can select the desired functionality according to their needs and proceed with the experiment step by step.

## 使用方法  
## Usage Instructions

### 主页面  
### Main Page

主页面是用户操作的起点，包含多个功能按钮，用户可根据需求选择相应的操作。  
The main page is the starting point for user operations, containing multiple functional buttons that users can select according to their needs.

各功能按钮的名称清晰明了，使得用户能够快速上手。  
The names of the functional buttons are clear and straightforward, allowing users to quickly get started.

### 影像分割  
### Image Segmentation 

在主页面点击“影像分割”后，系统会弹出相应窗口，用户可以进行图像的分割操作。  
Clicking "Image Segmentation" on the main page will bring up a corresponding window where users can perform image segmentation operations.

该窗口提供了多种按钮，功能包括选择影像、调整参数等。  
This window offers various buttons with functionalities, including selecting images and adjusting parameters.

### 自定义选取制作样本  
### Custom Sample Selection

用户可以手动选择最佳样本进行裁剪。  
Users can manually select the best samples for cropping.

通过拖动红色矩形框，选择合适的区域，点击裁剪按钮后，所选影像将被保存至指定文件夹。  
By dragging a red rectangle, users can select the appropriate region, and after clicking the crop button, the selected image will be saved to the specified folder.

### 制作标签  
### Label Creation

该功能允许用户打开 Labelme 工具，进行标签的制作。  
This functionality allows users to open the Labelme tool to create labels.

用户可以根据需要对图像中的各个区域进行标注，生成标签文件。  
Users can annotate various regions within images as needed and generate label files.

### 数据增强与训练  
### Data Augmentation and Training

工具支持数据增强功能，用户可以按照规则对数据进行增强。  
The tool supports data augmentation functionality, allowing users to enhance data according to rules.

同时，用户可以设置训练参数，开始训练模型，并实时查看训练进度。  
At the same time, users can set training parameters, start training the model, and monitor the training progress in real-time.

## 功能特点  
## Features

- **可视化界面**：用户友好的操作界面，降低了使用门槛。  
- **User-Friendly Interface**: An intuitive operational interface lowers the entry barrier for use.

- **多功能集成**：集成了影像分割、数据增强、标签制作等多项功能。  
- **Comprehensive Integration**: Integrates multiple functions such as image segmentation, data augmentation, and label creation.

- **高效性**：简化了深度学习实验过程，提高了工作效率。  
- **Efficiency**: Simplifies the deep learning experiment process and improves work efficiency.

- **支持多种文件格式**：支持 STH、TIF、KML、Json、SVG 等格式的转换与处理。  
- **Multi-format Support**: Supports conversion and processing of formats such as STH, TIF, KML, JSON, SVG, and more.

## 未来发展方向  
## Future Plans

随着技术的不断进步，宁南语义分割可视化工具也将持续更新与优化。  
With the continuous advancement of technology, the Ningshan Semantic Segmentation Visualization Tool will also continue to be updated and optimized.

未来可能的方向包括：  
Possible future directions include:

- **云端部署**：将软件部署到云端，方便用户随时随地使用。  
- **Cloud Deployment**: Deploy the software to the cloud, making it convenient for users to access it anytime, anywhere.

- **功能扩展**：根据用户反馈，新增更多实用功能。  
- **Feature Expansion**: Add more practical features based on user feedback.

## 结语  
## Conclusion
宁南语义分割可视化工具 V2.0 是一款致力于提升用户深度学习实验效率的工具。  
Ningshan Semantic Segmentation Visualization Tool V2.0 is a tool dedicated to enhancing the efficiency of users' deep learning experiments.

感谢您选择使用本软件，期待您的反馈与建议，以帮助我们不断改进和提升软件的功能与体验。  
Thank you for choosing this software, and we look forward to your feedback and suggestions to help us continuously improve and enhance the software's functionality and user experience.
