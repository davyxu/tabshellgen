# tabshellgen

生成跨平台的shell进行表格导出

# 参数

## type 
输出文件类型

* bat
	批处理
	
* bash
	Unix Shell
	
## template
输出文件模板, 使用go模板格式

* {{.ProtoList}}

	协议列表
	
* {{.TableList}}

	表格列表
	
## tablist
输入表格列表文件, 一行一个, 带相对路径

## protolist
输入协议列表文件, 一行一个, 带相对路径

## out
输出文件

# 例子
tabshellgen.exe --type=bat --template=Template_exportWin.txt --tablist=Template_Table.txt --protolist=Template_Proto.txt --out=exportWin.bat


# 链接

* 合并pbt为二进制

	https://github.com/davyxu/mergepbt
	
* 电子表格强力导出器

	https://github.com/davyxu/tabtoy


# 备注

感觉不错请star, 谢谢!

博客: http://www.cppblog.com/sunicdavy

知乎: http://www.zhihu.com/people/xu-bo-62-87

邮箱: sunicdavy@qq.com
