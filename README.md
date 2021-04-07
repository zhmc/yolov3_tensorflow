# yolov3_tensorflow

yolov3的tensorflow实现。
完全使用tensorflow的tensor operator来实现，没有使用python来计算，所以运算速度较快，达到和yolov3原本的darknet差不多的速度，耗时20ms左右。

效果如下图：
![效果图](https://raw.githubusercontent.com/zhmc/yolov3_tensorflow/master/data/result.jpg)

还有训练阶段的后向传播还未实现。
