# mnist_homework_project
## For 《高级程序设计c#（王晗）》
此项目是在c#课程（实际学的是python）的配套代码，由我们组（谢孝淼，杨柳，闫浩楠，武志远）提交并维护，我是组长武志远。


### Update1   2017-4-16
博客：http://www.jianshu.com/p/18211e7d96a5

主要给项目添加了数据集，包括train_data,train_label,test_data,test_label.写了解析数据集的代码input_file，可以把数据集的二进制流文件解析，
并转化成numpy.array类型，便于之后的进一步操作。main函数里暂时写了测试代码，证明input_file是可以正常工作的。

**依赖**：暂时需要 numpy，struct，matplotlib

**测试环境**:Ubuntu 16.04 LTS，python 2.7.12

**运行方法**：在当前目录下 ，在terminal里输入：
```
python main.py
```
