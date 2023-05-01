# ABAQUS-Python-Excel
Abaqus中Python导出后处理中的数据到Excel所需要的插件模块

- xlrd程序包是读excel文件中数据的Python程序包
- xlwt是在excel文件中写入数据的Python程序包
- xlutils是修改excel文件中数据的Python程序包

由于后处理过程中需要对excel中的数据进行读写操作，因此这三个程序包都必须有，否则运行会终止。

将三个插件模块文件夹（xlrd，xlwt，xlutils）放在ABAQUS安装目录下的python2.7文件夹中
