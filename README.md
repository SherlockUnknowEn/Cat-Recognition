# Cat-Recognition
神经网络算法识别猫


#### 测试:

 > python server.py

将会启动一个web服务，浏览器中键入 http://127.0.0.1:5000 可进入

---

网络模型：5层全连接神经网络，大小分别是 [12288, 20, 7, 5, 1]

---

* server.py 使用flask搭建的简单web服务，提供前台上传图片接口，后台调用recog.py进行识别，默认监听5000端口
* recog.py 神经网络的封装，需要读取params.obj参数
* params.obj 已训练好的参数，pickle序列化保存
* src: 训练代码
* datasets: 训练数据


#### 效果图：

![cat loading](https://github.com/SherlockUnknowEn/Cat-Recognition/blob/master/img/img1.png "cat")

![cat-re loading](https://github.com/SherlockUnknowEn/Cat-Recognition/blob/master/img/img1-re.png "cat-re")

![ji loading](https://github.com/SherlockUnknowEn/Cat-Recognition/blob/master/img/img2.png "ji")

![ji-re loading](https://github.com/SherlockUnknowEn/Cat-Recognition/blob/master/img/img2-re.png "ji-re")

