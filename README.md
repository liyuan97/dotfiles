# 我的 Dotfiles

这个仓库包含我的个人配置文件，使用 [Dotbot](https://github.com/anishathalye/dotbot) 进行管理。

## 包含配置

- Zsh 配置 (oh-my-zsh + powerlevel10k 主题)
- 常用插件 (git, z, docker, zsh-autosuggestions, zsh-syntax-highlighting)

## 安装

```bash
git clone https://你的仓库地址/dotfiles.git
cd dotfiles
./install
```

## 安装后

安装完成后，你可能需要：

1. 重启终端或运行 `source ~/.zshrc`
2. 如果是首次使用 powerlevel10k，会自动启动配置向导
3. 建议安装 MesloLGS NF 字体以获得最佳体验

## 自定义

你可以根据需要修改 `zshrc` 文件，然后重新运行 `./install` 应用更改。 