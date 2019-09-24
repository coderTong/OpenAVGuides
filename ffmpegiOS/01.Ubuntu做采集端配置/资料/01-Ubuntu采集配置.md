
### 1. 安装系统

 第一步使用虚拟机安装Ubuntu系统   我用的是Parallels Desktop 安装的

具体 安装,方法很多,这里不做赘述~

###  2. 开发环境配置

1. 安装zsh和git ----可有可无

```

sudo apt install zsh
sudo apt install git

sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"


```


2. 相关更新----可有可无


```

sudo apt-get update


```



3. 安装gcc , vim 

```

sudo apt-get install gcc


sudo apt-get install vim

```



4. 安装libasound2,  

```


sudo apt-get install libasound2

sudo apt-get install libasound2-dev


```



5. 安装v4l, x264


```


sudo apt-get install libv4l-dev

sudo apt-get install libx264-dev


```
