# Github托管代码

1.首先，在github创建一个仓库，与本地文件夹的同名即可，创建一个空仓库，根据命令提示进行下面操作

2.安装git，参照[安装教程](https://www.liaoxuefeng.com/wiki/896043488029600/896067074338496)

3.在根目录下新建一个文件取名`.gitignore`,打开，填入如下内容 
```python
# sphinx build folder
build
```  
本地的build是无须被上传的，所以我们直接push时忽略掉。


3.安装git成功后，我们来到文件夹的根目录，右键空白处，可见并选择`Git Bash Here`，随之弹出终端。根据第1步中的提示操作注意敲入命令使本地和远程仓库连接并推送。 
