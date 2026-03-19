# ⚙️ Dotfiles - StevenKlaus 配置文件 (Linux/WSL)

这是我在WSL中使用的核心配置文件仓库，通过 Git 进行版本控制和快速部署。

---

## 📦 包含的配置文件

本仓库通过符号链接 (Symbolic Link) 管理以下核心配置文件：

- **`.bashrc` / `.profile`**: Shell 环境变量、提示符 (`$PS1`) 和别名。
- **`.tmux.conf`**: Tmux 终端复用器配置（例如自定义前缀键）。
- **`.vimrc`**: Vim 文本编辑器配置。

---

## 🚀 快速部署指南 (新机器安装)

本指南用于在新安装的 Linux 或 WSL 环境上快速部署本配置，实现一键配置。

### 步骤 1: 克隆仓库

首先，确保新机器安装了 `git`，然后克隆本仓库。

```bash
# 确保 SSH 密钥已设置并添加到 GitHub
mkdir -p ~/git/
cd ~/git/
git clone https://github.com/DStevenFelix/dotfiles.git
