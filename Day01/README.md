# 学习要点
- 在 macOS 上安装 TensorFlow
- 机器学习新手使用入门


## 在 macOS 上安装 TensorFlow
pip3 install --upgrade tensorflow

验证安装成功
<https://www.tensorflow.org/install/install_mac>
```python
# Python
import tensorflow as tf
hello = tf.constant('Hello, TensorFlow!')
sess = tf.Session()
print(sess.run(hello))
```

## 机器学习新手使用入门
### 对鸢尾花进行分类
鸢尾花问题是监督式机器学习的一个示例, 即模型通过包含标签的样本加以训练。


