# Parallel-3DCNN

3D-CNNにおける、畳み込み層やプーリング層を並列構造にしたモデルです。
<br>This model is a parallel structure of convolutional and pooling layers in a 3D-CNN.

# Figure

![image](https://github.com/user-attachments/assets/ac5ccc65-eea4-4c6d-b4de-fc483ef55db4)

# Features

畳み込み層第1層のフィルタの様子を複数の視点から観察できるようにしています。
<br>The filter in convolution layer 1 can be observed from multiple perspectives.

入力動画は、[UCF101](https://www.crcv.ucf.edu/data/UCF101.php)を使用しています。
<br>The input video uses UCF101.

# Conv1 change

学習を行うことで、畳み込み層第1層のフィルタが変化します。
<br>Learning changes the filters in convolution layer 1.

例えば、学習前のフィルタは以下の様子ですが
<br>For example, the filter before the study looks like this

![Image](https://github.com/user-attachments/assets/5bc4ea59-1139-456b-be0d-ad342147159e)

学習後には以下のように、色に選択的であったり方向に選択的であったりと、それぞれの特徴を持つように変化します。
<br>After learning, they change to be selective for color or selective for direction, as shown below.

![Image](https://github.com/user-attachments/assets/b87b85b8-d0a0-4ed7-a9e1-57d644e376ca)
![Image](https://github.com/user-attachments/assets/e8f46f45-b91c-47d6-9111-26a0a3dc0612)


# Environment

プログラムに使用した環境は以下の通りです。
<br>The environment used for the program is as follows.

* OS：Microsoft Windows 11 Home 
* CPU：13th Gen Intel(R) Core(TM) i7-13700KF  3.40 GHz 
* memory：32.0 GB 
* storage：929 GB SSD 
* GPU：NVIDIA GeForce RTX 4070 Ti 
* CUDA：11.8 
* cuDNN：8.9.1 
* Python：3.10.11
* jupyter：1.0.0 
* matplotlib：3.7.1 
* numpy：1.23.5 
* scikit-learn：1.2.2 
* scipy：1.10.1 
* torch：2.0.1 
* torchvision：0.15.2 

# Note

I don't test environments under Linux and Mac.

# Author

* Kazuki Maekawa
* 所属：Osaka University

# License

"parallel3dcnn.ipynb" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

# References

* SoomroK, Roshan Zamir A, Shah M. UCF101: A Dataset of 101 Human Actions Classes From Videos in The Wild. CRCV-TR-12-01, 2012.
* 斎藤康毅. ゼロから作るDeep Learning ― Pythonで学ぶディープラーニングの理論と実装. オライリー・ジャパン, 2022.
* チーム・カルポ. 物体・画像認識と時系列データ処理入門. 秀和システム, 2021.
