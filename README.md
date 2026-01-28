# dotfiles

个人配置脚本集合

## Oh My Zsh 一键安装

自动安装 oh-my-zsh + powerlevel10k + 常用插件，支持 Ubuntu/Debian/CentOS/RHEL。

### 安装命令

**国外服务器：**

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/yyh361274777/dotfiles/main/install_ohmyzsh.sh)
```

**国内服务器（镜像加速）：**

```bash
# ghproxy 镜像
bash <(curl -fsSL https://mirror.ghproxy.com/https://raw.githubusercontent.com/yyh361274777/dotfiles/main/install_ohmyzsh.sh)

# jsdelivr CDN
bash <(curl -fsSL https://cdn.jsdelivr.net/gh/yyh361274777/dotfiles@main/install_ohmyzsh.sh)

# fastgit 镜像
bash <(curl -fsSL https://raw.fastgit.org/yyh361274777/dotfiles/main/install_ohmyzsh.sh)
```

### 包含内容

- **oh-my-zsh** - zsh 框架
- **powerlevel10k** - 主题（lean 风格）
- **zsh-autosuggestions** - 命令自动建议
- **zsh-syntax-highlighting** - 语法高亮

### 启用插件

```
git, z, sudo, colored-man-pages, extract
docker, kubectl, history, copypath, copyfile, web-search
zsh-autosuggestions, zsh-syntax-highlighting
```

### 重新配置主题

```bash
p10k configure
```
