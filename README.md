# config
* GIT Mercurial显示分支名
* 首先安装ZSH和ON My SSH
* 其次设置Zsh主题, 参考wenming.zsh-theme
* 在.zshrc中添加
* ZSH_THEME = 'wenming'
* plugins = (git mercurial)
* 重置Iterm2配色:defaults delete com.googlecode.iterm2
*自动提示命令
当我们输入命令时，终端会自动提示你接下来可能要输入的命令，这时按 → 便可输出这些命令，非常方便。

设置如下：

1.克隆仓库到本地 ~/.oh-my-zsh/custom/plugins 路径下

git clone git://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions

2.用 vim  ~/.zshrc 打开文件，下滑找到插件设置命令，默认是 plugins=(git) ，我们把它修改为
plugins=(zsh-autosuggestions git)
