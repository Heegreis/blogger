目的是要整理深度學習的東西，並預計希望弄出一個路線地圖或學習地圖，實現網路的部分以 PyTorch 作為工具。  
雖然進度非常之緩慢就是了...

這篇文章暫時作為規劃這些東西的筆記，以及筆者自己在學習深讀學習的規劃。

而每個網路模型，都會有以下事情要做:  
 - 讀論文
 - 實作

這些筆者不一定會照順序做。
[readmore]
**目錄**  
[TOC]
# 影像分類
## LeNet
### 論文 (尚未開始):  
[Gradient-based learning applied to document recognition](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)  
雖然該模型幾乎是卷積神經網路之祖，但論文有49頁之多，聽說後半主要是數學還其他各種實驗之類的，筆者就先不去詳讀這篇論文了。

### 實作 (待完善):  
筆者已透過 pytorch 實作了，但還想將細節搞得更懂一些，程式碼弄得更有系統性與泛用性，所以算是未完成。

### 手刻實作 (尚未開始):
因為算是卷積網路的根源，所以預計要弄一個手刻版本來完整弄懂該網路。
## AlexNet
### 論文 (尚未開始)
[Imagenet classification with deep convolutional neural networks](http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)

### 實作 (進行中)
單純使用預訓練模型 (進行中)

遷移學習 (尚未開始)

重新訓練 (尚未開始)
# 參考資料

*最後編輯時間:2018/5/10*

<!--tags:
-->
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NDk4Mjg1NThdfQ==
-->