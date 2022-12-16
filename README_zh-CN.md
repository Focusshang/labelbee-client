<div align="center">
<article style="display: flex; flex-direction: column; align-items: center; justify-content: center;">
    <p align="center"><img width="300" src="https://github.com/opendatalab/labelU/blob/main/images/labelU-logo.svg" /></p>
    <h1 style="width: 100%; text-align: center;"></h1>
    <p align="center">
        简体中文 | <a href="./README.md" >English</a>
    </p>
</article>
    
<p align="center">
<img src="./docs/assets/main.png">
</p>
   
</div>

## 简介

LabelU 是一款中文的开源数据标注工具。目前具备拉框、多边形、标点、标线、分类、描述等图像标注能力，能够支持目标检测、图像分类、实例分割、文本转写、轮廓线检测、关键点检测等计算机视觉任务场景，通过工具的自由组合即可自定义标注任务，支持COCO、MASK格式数据导出。

## 快速开始

### 下载并安装miniconda

https://docs.conda.io/en/latest/miniconda.html

### 安装并激活python = 3.10

```bash
conda create -n labelu --python=3.10
conda activate labelu
```

### 安装labelu

```bash
pip install labelu
```

### 启动labelu，默认访问地址：http://localhost:8000

```bash
labelu
```

## 特性

- 统一，提供6种图像标注工具，通过简单可视化或Yaml配置即可标注
- 灵活，多种工具可自由组合使用，满足大部分图像标注需求
- 通用，支持导出多种数据格式，包括Labelbee、COCO、Mask

## 支持场景

### 视觉
- 目标检测：车辆、车牌、行人、人脸、工业部件等检测场景
- 图像分类：检测对象分类、目标特征、是非判断等分类场景
- 实例分割：人体分割、全景分割、可行驶区域分割、车辆分割等
- 文本转写：车牌、发票、保单、招牌等文本检测和识别
- 轮廓线检测：人体轮廓线、车道线等定位线场景
- 关键点检测：人脸人体关键点、车辆关键点、路沿关键点等定位场景

## 快速上手

 [使用说明](./docs/README.md) 

## 标注格式说明

[LabelU 标注格式](./docs/annotation/README.md)

## 技术交流

![8faa20cf-6898-4b16-b4cc-174795159f2c](https://user-images.githubusercontent.com/25022954/208056502-d752ecf3-783a-48ab-9742-bb30e42cbc85.jpg)

## 友情链接

- [LabelU-kit](https://github.com/opendatalab/labelU-Kit)（本工具都是通过 LabelU-kit 进行开发）

## 开源许可证

该项目使用 [Apache 2.0 license](./LICENSE).
