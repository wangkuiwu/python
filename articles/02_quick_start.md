
### Python-02 快速入门

#### 1. Mac安装Python
##### 1.1 安装Python3  
(1) 通过下面指令安装Python3   

```
$ brew install python3
```  
会自动下载最新的python3 和 pip3  

(2) 查看安装python的版本  

```
$ python3  --version
$ pip3  --version   
```  

##### 1.1 安装Python2.7
(1) 通过下面指令安装Python2.7

```
$ brew install python@2
```   
安装完毕后会显示python路径   
 
(2) 修改PATH参数，添加python路径。例如，修改~/.zshrc或~/.bashrc 
 
```
export PATH="/usr/local/Cellar/python@2/2.7.15/bin:$PATH"
```


#### 2. 运行hello world 
(1) 编辑01_hello.py文件。  

```
#!/usr/bin/env python3
# -*- coding: utf-8 -*-
print('hello world')
```

(2) 运行01_hello.py文件。

```
$ python3 01_hello.py
```  
或者

```
$ ./01_hello.py
```

输出结果：  
```
hello world  
```  

说明：  
1) `#!/usr/bin/env python3`表示用`./01_hello.py`执行时，用python3解析该程序。  
2) `# -*- coding: utf-8 -*-`表示源文件支持UTF-8编码(可以显示中文)。   
3) `print('hello world')`表示输出`hello world`。  

