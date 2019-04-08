# 项目输出
项目输出是当前项目的阶段性成果，可以包含处理完的数据文件，训练完成的模型文件，等。

### 保存项目输出
用户可在K-Lab主界面选择 **生成项目输出** 按钮选择

![image description](/image/output-gen.png)

项目的输出文件不设大小限制，但单个项目至多可选择 **5** 个文件作为输出。当项目有了新的输出文件，或原输出发生了变化、删改时，请再次选择输出文件。

### 输出预览
对于数据文件，K-Lab 提供了常见的 `.csv`, `.tsv` 等格式的预览。

![image description](/image/preview-output-datafile.png)

对于模型文件, K-Lab支持解析并可视化展示模型结构。支持的框架包括 **ONNX** (`.onnx`, `.pb`, `.pbtxt`), **Keras** (`.h5`, `.keras`), **CoreML** (`.mlmodel`), **MXNet** (`.model`) 以及 **TensorFlow Lite** (`.tflite`)。 也支持最新版本的 **Caffe** (`.caffemodel`, `.prototxt`), **PyTorch** (`.pth`), **Torch** (`.t7`), **CNTK** (`.model`, `.cntk`), **Darknet** (`.cfg`), **scikit-learn** (`.pkl`), **TensorFlow.js** (`.pb`) 和 **TensorFlow** (`.pb`, `.meta`, `.pbtxt`)。

![image description](/image/preview-model.png)

点击模型的节点也可差看具体参数细节和文档

![image description](/image/preview-model-node.png)


### 使用输出
输出文件可以作为一种 **数据源** 挂载进别的项目。详情请参考 [创建项目](./create_lab.md)
