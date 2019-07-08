# analyze_xlnet
適当にXLNetのPre-trainedモデルで推論するためのサンプル

# How to use

```shell
pip install sentencepiece tensorboardx

git clone https://github.com/zihangdai/xlnet.git
git clone https://github.com/tyo-yo/analyze_xlnet.git

mv analyze_xlnet/analyze_xlnet.2019.07.01.ipynb xlnet/

cd xlnet
wget https://storage.googleapis.com/xlnet/released_models/cased_L-24_H-1024_A-16.zip
unzip cased_L-24_H-1024_A-16.zip

jupyter notebook
# 後はjupyterでanalyze_xlnet.2019.07.01.ipynbを開いて実行する
```



# Requirements

* tensorflow
* sentencepiece
* tensorboardX
  * 可視化をする際にTensorboardを簡単に利用するため



# Images

![image-20190708203632800](/Users/tyoyo/Library/Application Support/typora-user-images/image-20190708203632800.png)

![image-20190708203644526](/Users/tyoyo/Library/Application Support/typora-user-images/image-20190708203644526.png)

# Slides

* Coming soon!