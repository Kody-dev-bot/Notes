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
4. 自定义主题
```bash
wget -O $ZSH_CUSTOM/themes/haoomz.zsh-theme https://cdn.haoyep.com/gh/leegical/Blog_img/zsh/haoomz.zsh-theme
```
5. 安装插件
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```