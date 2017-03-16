# solarized-powerline
Solarized powerline style theme for zsh

Forked from [agnoster's theme](https://gist.github.com/3712874) and influenced by [maverick2000's theme](https://github.com/maverick2000/zsh2000) and [iijeremyFreeAgent's theme](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).

### Preview
![preview](https://raw.github.com/houjunchen/solarized-powerline/master/preview.png)

![preview2](https://raw.github.com/houjunchen/solarized-powerline/master/preview2.png)

### Prerequisites

Install your favorite version of
[Powerline-patched fonts](https://github.com/powerline/fonts)

### Installation

```
git clone https://github.com/houjunchen/solarized-powerline.git
cd solarized-powerline
ln -s solarized-powerline.zsh-theme ~/.oh-my-zsh/themes/solarized-powerline.zsh-theme
```
Note: To avoid `too many levels of symbolic links`, you may need to use absolute target in `ln -s`.

Modify ~/.zshrc setting

```
ZSH_THEME="solarized-powerline"
```
