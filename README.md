# kmnistについて
kmnist(kuzushiji-MNIST)を解析するために用いたソースコードとデータセットが格納されている.

# dataset
http://codh.rois.ac.jp/kmnist
人文学オープンデータ共同利用センターが提供している Kuzushiji Datasetを利用する.

# download.py
https://github.com/rois-codh/kmnist で提供されているソースコードで, datasetをダウンロードするために使用する.

# benchmarks
benchmarksにはhttps://github.com/rois-codh/kmnist で公開されている kuzushiji_mnsit_cnn.py と kuzushiji_mnist_knn.py が格納されている. 特にkuzushiji_mnist_cnn.pyを軸に解析を行っていく.

# deep
kuzushiji_mnist_cnn.py よりも階層の深いモデル.
kerasが提供しているサンプルモデルの cifar10_cnn.pyを参考に構成. 


# 開発環境
1. CPU
  1. MacBook Pro
  1. anaconda 2019.03 for macOS installer
  1. conda 4.8.3
  1. python 3.7.4

1. GPU
  1. AWS EC2 p2.xlarge
  1. ubuntu 18.04(Deep Learning AMI)
  1. tensorflow_p36



# reference
http://codh.rois.ac.jp/kmnist/
https://github.com/rois-codh/kmnist
https://keras.io/
https://github.com/keras-team/keras/tree/master/examples
