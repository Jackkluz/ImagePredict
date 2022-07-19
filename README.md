# ImagePredict
Utilize DenseNet AI to read and predict the subject of JPGs.

**Requires Python 3.7**

The program is currently set to run using DenseNet. If you would like to change to a lightweight and faster AI please use the mobilenet.

MobileNet setup:
alter lines 7 & 8 w/
- prediction.setModelTypeAsMobileNetV2()
- prediction.setModelPath(os.path.join(execution_path, "mobilenet_v2.h5"))

To change the photo analyzed, please change the name of the jpg in line 12 to a desired jpg located in the PWD.
The output is the AI's guess with the probability. This is not my AI and it does not produce accurate results consistently.
