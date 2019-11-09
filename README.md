#vim backup<br>
##vim配置文件的备份
此配置文件的vim具有一下功能：<br>
    >   新建文件可以自动添加头文件。具体内容可以自己修改。<br>
    >   配置了YCM 自动补全插件，使用manjaro可以使用AUR自动编译安装，省事省力。<br>
    >   语法高亮、行号等vim基础功能<br>
    >   Ｆ5一键运行当前代码。支持语言：C、C++、Ｐｙｔｈｏｎ、go、java以及MK。<br>
配置过程：<br>
   
    >   安装Vundle<br>
        git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
   >    将.vimrc放在用户**主目录**下<br>
   >    打开vim运行**“:PluginInstall”**命令。<br>
