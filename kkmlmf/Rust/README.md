# RUST 🦀

## 安装(Linux、wsl2)

### 安装jupyter-notebook
```
sudo apt install jupyter-notebook
```

### 安装rustup
```bash
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```

会看到输出
```bash
Rust is installed now. Great!
```

### 安装EvCxR

重新打开一个终端，输入
```bash
cargo install evcxr_jupyter
```

会看到输出
```bash
    Finished `release` profile [optimized] target(s) in 3m 27s
  Installing /home/kokomi/.cargo/bin/evcxr_jupyter
   Installed package `evcxr_jupyter v0.21.1` (executable `evcxr_jupyter`)
```

### 安装 Rust的Jupyter 内核
```bash
evcxr_jupyter --install
```

输出
```bash
Installation complete
```

### 启动jupyter
```bash
jupyter notebook
```

点击右上角NEW即可创建Rust的notebook

### （可选）配置镜像

打开配置文件
```bash
nano ~/.bashrc
```

在文件末尾添加以下内容
```bash
export RUSTUP_DIST_SERVER="https://rsproxy.cn"
export RUSTUP_UPDATE_ROOT="https://rsproxy.cn/rustup"
```

保存并退出：按 Ctrl+X，输入 Y 确认，再按 Enter。

打开配置文件
```bash
nano ~/.cargo/config.toml
```

输入以下内容
```conf
[source.crates-io]
replace-with = 'rsproxy-sparse'
[source.rsproxy]
registry = "https://rsproxy.cn/crates.io-index"
[source.rsproxy-sparse]
registry = "sparse+https://rsproxy.cn/index/"
[registries.rsproxy]
index = "https://rsproxy.cn/crates.io-index"
[net]
git-fetch-with-cli = true
```

保存并退出：按 Ctrl+X，输入 Y 确认，再按 Enter。

## none
