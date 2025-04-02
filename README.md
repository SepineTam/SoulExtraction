# SoulExtraction
Mathematical video action recognition.

## 实现逻辑
1. 将视频拆解成若干帧
2. 等间距抽取帧（以减少计算量，避免算力资源的浪费）
3. 将每一帧进行向量化处理
4. 与标准动作进行比对（通过余弦方法求图片间的距离）
5. 排序，输出最相似的动作

## 技术栈
- Python 3.11
- OpenCV
- Numpy
- scikit-learn

