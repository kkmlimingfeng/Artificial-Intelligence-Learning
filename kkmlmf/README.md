# pytorch study

![PyTorch](https://img.shields.io/badge/PyTorch-2.8-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**可以先打开 Installed，将需要安装的包装一下**

---

## 目录

- [📘 2025年12月20日｜PyTorch 入门笔记](#-2025年12月20日pytorch-入门笔记)
- [📗 2025年12月21日｜Transformer 详细教程](#-2025年12月21日transformer-详细教程)
- [📙 2025年12月27日 - 12月29日｜Stable Diffusion 学习笔记](#-2025年12月27日--12月29日stable-diffusion-学习笔记)
- [📕 2026年3月4日｜Mamba3 代码解析](#-2026年3月4日mamba3-代码解析)
- [📒 2026年3月9日｜Copaw 部署教程](#-2026年3月9日copaw-部署教程)
- [📓 2026年5月21日 - 2026年5月26日｜大模型使用与微调](#-2026年5月21日--2026年5月26日大模型使用与微调)

---

## 📘 2025年12月20日｜PyTorch 入门笔记

**文件位置：** [打开 1号 ipynb](./1%E5%8F%B7.ipynb)

### 内容介绍
- 张量及其运算
- 拓展：einops 的简单使用
- 自动微分及反向传播和梯度
- 神经网络简单实现
- 拓展：tqdm 的简单使用
- 拓展：Dataset 和 Dataloader 的简单使用

### 能学会什么
- PyTorch 常用函数的调用
- 学会利用 PyTorch 创建简单的神经网络
- 学会深度学习常用的 einops 和 tqdm 的使用
- 学会深度学习常用的代码框架（大部分数据通用）

### 其他
这是本人突发奇想，参考自 pytorch123.com，结合豆包 AI 助手，做的简单的 PyTorch 入门笔记，有不对的地方敬请指出。

---

## 📗 2025年12月21日｜Transformer 详细教程

**文件位置：** [打开 2号 ipynb](./2%E5%8F%B7.ipynb)

### 内容介绍
- 官方 Transformer 代码运行尝试（先看看效果）
- 嵌入层（用官方的）和位置编码（自己实现）
- 多头自注意力（官方的和自己实现）
- 编码器（官方的和自己实现）
- 解码器（官方的和自己实现）
- Transformer（自己实现以及简单训练测试效果）

---

## 📙 2025年12月27日 - 12月29日｜Stable Diffusion 学习笔记

**文件位置：** [打开 3号 ipynb](./3%E5%8F%B7.ipynb)

### 内容介绍
- 使用 Stable Diffusion 进行文生图和图生图（4G 显存显卡即可运行，可 NSFW）
- 使用 Waifu-Diffusion 生图，4G 显存可跑
- 使用 Z-Image 生图，需要 14G 显存
- 使用 lightx2v 和 wan2.1 文生视频 1.3B 模型（wan2.2-14B 还未成功）
- 后续计划：
  - 使用 ControlNet 生成可控图像
  - LoRA 微调
  - Stable Diffusion 的详细实现
  - ComfyUI 学习

---

## 📕 2026年3月4日｜Mamba3 代码解析

**文件位置：** [打开 4号 ipynb](./4%E5%8F%B7.ipynb)

### 内容介绍
- Mamba3 使用说明
- Mamba3 模型完整分步实现
- Mamba3 模型测试
- 使用 Mamba3 训练模型并生成文本

---

## 📒 2026年3月9日｜Copaw 部署教程

**文件位置：** [打开 5号 pdf](./5%E5%8F%B7.pdf)

### 内容介绍
- 阿里国产版“龙虾” Copaw 的全程免费部署教程

---

## 📓 2026年5月21日 - 2026年5月26日｜大模型使用与微调

**文件位置：** [打开 6号 ipynb](./6%E5%8F%B7.ipynb)

### 内容介绍
- GPU 用量检测和缓存清理
- 模型加载、vLLM 部署、OpenAI 接口使用
- 8bit / 4bit 量化
- 微调技术介绍：LoRA、QLoRA
- 模型剪枝：非结构化、结构化、2:4 半结构化
- 知识蒸馏概念介绍（无代码实现）
