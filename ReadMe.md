# **说明**
## **工具功能说明**
* 考研大数据爬取与分析工具（主要爬取与分析研招网（ https://yz.chsi.com.cn/ ）上的所有与招生有关的网页）
## **代码设计说明**
### **spider**
* 采集器模块
* 为采集网页数据提供支持
### **selector**
* 筛选器模块
* 为对采集到的数据进行筛选/过滤提供支持
### **analyser**
* 分析器模块
* 为数据分析提供支持
### **storer**
* 存储器模块
* 为存储与读取数据提供支持
### **main-01-getData**
* 程序入口模块
* 为打开/启动程序以及调用执行相关库函数提供支持
* 具体的，启动后开始进行第一阶段的数据采集工作
### **main-02-analyzeData**
* 程序入口模块
* 为打开/启动程序以及调用执行相关库函数提供支持
* 具体的，启动后开始进行第二阶段的数据分析工作
### **design pattern**
* 设计模式模块
* 为类的设计模式（如单例模式）提供支持!
* 具体的，我们暂时提供了单例模式的装饰器与仅添加添加获取单例方法的装饰器（未重新new方法）
### **multiple**
* 加速模块模块
* 暂时提供多进程加速（注意在使用多进程进行异步运行时不能运行采用单例模式设计的类的方法）

### **图解**
![图片无法正常加载，请联系作者](https://ws1.sinaimg.cn/large/d1aeccfaly1g2utd3bwkaj20ga0i4t8u.jpg)

## **代码开源及博客更新地址**
### **GitHub's address:**
* https://github.com/COCO5666/Graduate_admissions_data_analysis_tool
### **CSDN's address:**
* https://blog.csdn.net/COCO56/article/details/82317275