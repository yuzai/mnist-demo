### 解决问题
mnist手写字体识别

### 运行方法
1. yarn
2. npm run watch

### more
1. 不要吐槽代码风格，一切都是以能运行为标准
2. 代码参考tensorflow.js示例修改而来
3. 有问题随便问哈@maxiaobo

### 演示地址

打包没有经过优化，完全参照parcel默认配置来的，js包可能较大，同时静态文件是直接丢在github上的，速度会比较慢，不要介意

http://blog.maxiaobo.com.cn/mnist-demo/dist/

# TensorFlow.js Example: Training MNIST

This example shows you how to train MNIST (using the layers API).

You can check out the tutorial that accompanies this example [here](https://js.tensorflow.org/tutorials/mnist.html).

This model will compute accuracy over 1000 random test set examples every 5
steps, plotting loss and accuracy as the model is training. Training time can
be reduced by computing accuracy over fewer examples less often.

Note: currently the entire dataset of MNIST images is stored in a PNG image we have
sprited, and the code in `data.js` is responsible for converting it into
`Tensor`s. This will become much simpler in the near future.

[See this example live!](https://storage.googleapis.com/tfjs-examples/mnist/dist/index.html)
