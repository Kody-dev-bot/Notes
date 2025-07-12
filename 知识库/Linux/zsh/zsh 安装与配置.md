1. 安装基本工具
```bash
sudo pacman -S git curl zsh
```
2. 设置默认终端为 zsh（**注意：不要使用 sudo**）。
```bash
chsh -s /bin/zsh
```
3. 安装 oh-my-zsh

| Method                                       | Command                                                                              |
| -------------------------------------------- | ------------------------------------------------------------------------------------ |
| **curl**                                     | `sh -c "$(curl -fsSL https://install.ohmyz.sh/)"`                                    |
| **wget**                                     | `sh -c "$(wget -O- https://install.ohmyz.sh/)"`                                      |
| 国内curl[镜像](https://gitee.com/pocmon/ohmyzsh) | `sh -c "$(curl -fsSL https://gitee.com/pocmon/ohmyzsh/raw/master/tools/install.sh)"` |
| 国内wget[镜像](https://gitee.com/pocmon/ohmyzsh) | `sh -c "$(wget -O- https://gitee.com/pocmon/ohmyzsh/raw/master/tools/install.sh)"`   |

