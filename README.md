# Neural-Style
A TensorFlow Project of Neural Style
## **代码实现**

**环境介绍**
- Python3.6
- TensorFlow 1.2
- VGG19
- CPU i5-6200U(笔记本)
## **实现效果**

**我们的原图是这样的：**

![这里写图片描述](http://img.blog.csdn.net/20180108210931718?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzA2MTE2MDE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

**风格是这样的：**

![这里写图片描述](http://img.blog.csdn.net/20180108212407292?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzA2MTE2MDE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

**我们在cmd命令行中打入下面代码(我的图片都放在examples/下）：**

> python neural_style.py --content examples/cat.jpg --styles examples/2-style1.jpg --output y-output.jpg

![这里写图片描述](http://img.blog.csdn.net/20180108213158508?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzA2MTE2MDE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

**然后我们看到计算机已经开始进行风格转移:**

![这里写图片描述](http://img.blog.csdn.net/20180108213257762?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzA2MTE2MDE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
（ps:我可怜的笔记本不停地跑了两个小时）

**转移结束后我们可以看到输出的图片是这样的：**

![这里写图片描述](http://img.blog.csdn.net/20180108212431248?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzA2MTE2MDE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

Neural Style很有趣，我们可以通过改变参数去做很多风格的测试，会有不一样的效果。
