# Artificial-Intelligence-Learning

> 人工智能各方面入门到入土教程（更新中）
> > 本教程的目标是了解+会用，并非深入底层

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.8-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Last Commit](https://img.shields.io/badge/Last%20commit-2026--06--02-blue?style=for-the-badge)

---

## 协作者
<a href="https://github.com/kkmlimingfeng/Artificial-Intelligence-Learning/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kkmlimingfeng/Artificial-Intelligence-Learning&columns=6&max=10&anon=1" />
</a>

---

## 仓库导航

- [快速上手-Anaconda](#快速上手anaconda版适用于windowsmacoslinuxwsl2)
- [快速上手-uv](#快速上手uv版适用于macoslinuxwsl2)
- [仓库结构](#仓库结构)
- [文件夹介绍](#文件夹介绍)
- [说明](#说明)

---

## 快速上手（Anaconda版，适用于Windows、macOS、Linux、wsl2）

### 1. 获取项目

先把本项目克隆到本地：

```bash
git clone https://github.com/kkmlimingfeng/Artificial-Intelligence-Learning.git
```

如果你下载的是压缩包，请先解压；如果通过git clone，直接进入项目根目录即可：

```bash
cd Artificial-Intelligence-Learning
```

### 2. 创建并激活 Conda 环境

建议使用 Python 3.12 创建独立环境：

```bash
conda create -n your_env_name python=3.12 -y
conda activate your_env_name
```

（可选）安装uv，加速安装包的速度
```bash
pip install uv
```

### 3. 配置 pip 清华源镜像 并 安装 notebook

临时使用清华源安装notebook可这样写：

```bash
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple notebook
```

如果你想长期使用清华源，可以配置为默认镜像：

```bash
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```

然后安装 `notebook`：

```bash
pip install notebook
```

### 4. 开始使用

安装完成后，启动 Jupyter Notebook，然后就可以直接打开仓库里的 `.ipynb` 文件开始学习和实验了。

```bash
jupyter notebook
```
或者
```
jupyter lab
```

按住ctrl，点击命令行里的链接打开本项目

---

## 快速上手（uv版，适用于macOs、Linux、wsl2）

### 1. 获取项目

先把本项目克隆到本地：

```bash
git clone https://github.com/kkmlimingfeng/Artificial-Intelligence-Learning.git
```

如果你下载的是压缩包，请先解压；如果通过git clone，直接进入项目根目录即可：

```bash
cd Artificial-Intelligence-Learning
```

### 2. 创建并激活 uv 环境

（未安装uv）安装uv

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
uv --version
```

建议使用 Python 3.12 创建独立环境：

```bash
uv venv --python 3.12
```

### 3. 配置 pip 清华源镜像 并 安装 notebook

临时使用清华源安装notebook可这样写：

```bash
uv pip install -i https://pypi.tuna.tsinghua.edu.cn/simple notebook
```

如果你想长期使用清华源，可以配置为默认镜像：

```bash
uv pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```

然后安装 `notebook`：

```bash
uv pip install notebook
```

### 4. 开始使用

安装完成后，启动 Jupyter Notebook，然后就可以直接打开仓库里的 `.ipynb` 文件开始学习和实验了。

```bash
jupyter notebook
```
或者
```
jupyter lab
```

按住ctrl，点击命令行里的链接打开本项目

---

## 仓库结构

- `package/`：存放无法直接 pip 下载的包
- `kkmlmf/`：
- `LittleBird/`：
- `Tao/`：

---

## 文件夹介绍

### 🧠 kkmlmf
> kkmlmf的文件夹
>
> - PyTorch 入门
> - Transformer 详细教程
> - Stable Diffusion 相关实践
> - Mamba3 代码解析
> - Copaw 的 WSL 安装部署教程
> - 大模型的加载、部署、使用、量化、剪枝、微调
> - Markdown与Mermaid教学
> - Agent入门
>
> [📂 进入 kkmlmf 文件夹](./kkmlmf/)

### 🌿 LittleBird
> Rhang的文件夹
>
> - Rhang的学习笔记
> - 期待更新
>
> [📂 进入 LittleBird 文件夹](./LittleBird/)

### 🌸 Tao
> TaoAi的文件夹
>
> - TaoAi的学习笔记
> - 期待更新
>
> [📂 进入 Tao 文件夹](./Tao/)

---

## 说明

本仓库以 Jupyter Notebook 为主，内容偏实践和记录性质，适合用于：

- PyTorch 学习
- Transformer / Diffusion / LLM 学习
- Markdown
- 模型使用、部署和优化
- Agent

欢迎交流与指正。
