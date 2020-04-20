
# 思必拓工具
应用主要用于调试模块 排查问题  以及演示工具类的接口调用

* 串口操作和GPIO控制API在以下链接中 https://www.showdoc.cc/12541?page_id=107025
* 配置文件预览以及编辑
* GPIO预览以及控制
* 基站信息
* GPS信息

库包括串口以及其他工具类 可通过jitpack加载库使用

**依赖说明**：

1.在项目的build.gradle中添加以下
```xml
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
在modle的依赖中添加以下
```xml
	dependencies {
		implementation 'com.github.SpeedataG:Device:1.6.4'
	}

 ``` 
