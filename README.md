vim backup  
================
vim配置文件的备份
----------------
* 此配置文件的vim具有一下功能：
        
        1.新建文件可以自动添加头文件。具体内容可以自己修改。 
        2.配置了YCM 自动补全插件，使用manjaro可以使用AUR自动编译安装，省事省力。 
        3.语法高亮、行号等vim基础功能 
        4.Ｆ5一键运行当前代码。支持语言：C、C++、Ｐｙｔｈｏｎ、go、java以及MK. 
    
* 配置过程：
   
        1.安装Vundle<br>
             git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
        2.将.vimrc放在用户主目录下
        3.打开vim运行“:PluginInstall”命令
