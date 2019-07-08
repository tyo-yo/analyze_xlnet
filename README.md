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

![Imgur](https://i.imgur.com/NR8sjrm.png)

![Imgur](https://i.imgur.com/6USTTAf.png)





# Slides

* Coming soon!