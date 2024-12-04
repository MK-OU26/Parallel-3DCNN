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

* 所属：Osaka University

# License

"parallel3dcnn.ipynb" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

# References

* SoomroK, Roshan Zamir A, Shah M. UCF101: A Dataset of 101 Human Actions Classes From Videos in The Wild. CRCV-TR-12-01, 2012.
* 斎藤康毅. ゼロから作るDeep Learning ― Pythonで学ぶディープラーニングの理論と実装. オライリー・ジャパン, 2022.
* チーム・カルポ. 物体・画像認識と時系列データ処理入門. 秀和システム, 2021.
