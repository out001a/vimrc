# vimrc
vimrc using Vundle

## 一、 使用
1. 安装Vundle `git clone http://github.com/gmarik/vundle.git ~/.vim/bundle/Vundle.vim`
2. 将`.vimrc`文件拷贝到家目录（注意备份）
3. 安装插件，在vim中执行 `:BundleInstall`
4. 卸载插件，先删除`.vimrc`中对应的Bundle，再在vim中执行 `:BundleClean`

## 二、 Vundle的常用命令
```
:BundleList             -列举列表(也就是.vimrc)中配置的所有插件  
:BundleInstall          -安装列表中的全部插件  
:BundleInstall!         -更新列表中的全部插件  
:BundleSearch foo       -查找foo插件  
:BundleSearch! foo      -刷新foo插件缓存  
:BundleClean            -清除列表中没有的插件  
:BundleClean!           -清除列表中没有的插件  
```

## 三、 参考
* http://blog.csdn.net/jiaolongdy/article/details/17889787/
