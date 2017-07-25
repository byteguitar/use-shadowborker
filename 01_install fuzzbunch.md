# use-shadowborker
## 下载攻击工具
  
## 环境要求
### 1.在windows7下面必须python2.6 ,由于本来安装了python2.7 ，重新安装一个python2.6.
### 2.修改了环境变量
    比如 x:\python26 x:\python26\scripts ,这两个目录必须加入    
### 3.安装 pywin32
     如果用python 2.6使用pip ，必须先安装 easy-install ，就要下载easy-install,  然后执行 Python  setup-py instal
     然后安装 pip  ，easy_install.exe 在x:\python26\scripts目录下，然后执行 easy_install install pip 就可以了 
       
### 4.在副fuzzbunch目录下运行fb.py 出错，win32pipe出错，这是个大坑
    拷贝 X:\Python26\Lib\site-packages\pywin32_system32\*
    至 C:\Windows\System32
   
     
