
![](https://github.com/ma6174/vim/raw/master/screenshot.png)

简易安装方法：

打开终端，执行下面的命令就自动安装好了：

wget -qO- https://raw.github.com/ma6174/vim/master/setup.sh | sh -x
或者自己手动安装：(以ubuntu为例)

    安装vim sudo apt-get install vim
    安装ctags：sudo apt-get install ctags
    安装一些必备程序：sudo apt-get install xclip vim-gnome astyle python-setuptools
    python代码格式化工具：sudo easy_install -ZU autopep8
    sudo ln -s /usr/bin/ctags /usr/local/bin/ctags
    clone配置文件：cd ~/ && git clone git://github.com/ma6174/vim.git
    mv ~/vim ~/.vim
    mv ~/.vim/.vimrc ~/
    clone bundle 程序：git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    打开vim并执行bundle程序:BundleInstall
    重新打开vim即可看到效果
    
    
    第二种安装(简单式)
    $ git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
$ git clone https://github.com/windy/ruby-vimrc.git

$ cp ruby-vimrc/vimrc ~/.vimrc

$ vim
  # 输入以下指令
  :PluginInstall( in vim input this command)
  # 等待插件安装完成, 重启 vim, OK
  :q!
    
