<h1><center>SE-TCNAE</center></h1>



- ##### 碩士論文 --> [鄭睿閎-碩士論文](https://github.com/iinoshirozheng/gear-tcn-ae/blob/main/%E9%84%AD%E7%9D%BF%E9%96%8E_%E7%A2%A9%E5%A3%AB%E8%AB%96%E6%96%87.pdf)

# 神經網路程式碼結構

## 程式碼
### 齒輪磨耗與缺陷分類與檢測
- `wear_tcn.py`：齒輪磨耗程度檢測程式碼
- `tcn_classification_1Channel.py`：SE-TCN 齒輪缺陷分類（單軸）
- `tcn_classification.py`：SE-TCN 齒輪缺陷分類（三軸）
- `tcn_classification_ORG.py`：TCN 齒輪缺陷分類（三軸）
- `gear_tcn_ae.py`：齒輪缺陷檢測程式碼

## 資料擷取
### 齒輪振動數據
- `bot`（資料夾）：輕度齒輪缺陷資料
- `mid`（資料夾）：中度齒輪缺陷資料
- `top`（資料夾）：重度齒輪缺陷資料



##### ( 由於數據資料檔案過大，可以下載我的雲端連結 --> [Data](https://drive.google.com/drive/folders/1hqApdd6KRoPuIHYSnkE0VTesJOmIphD-?usp=sharing))

### 論文中所使用之程式碼皆是基於最基本的 TCN (時間卷積神經網路) 的程式所轉寫 --> [點擊此處跳轉至原始碼](https://github.com/philipperemy/keras-tcn)

#### (上面連結非原作者程式碼 此為好心的人所幫忙寫的 TCN 網路層，可以簡易的調用網路於 Tensorflow Keras 中)

此程式碼使用到了套件 [keras-tcn](https://github.com/philipperemy/keras-tcn) 來完成 TCN 模塊，並加入了ＳＥ模塊。 

代碼中參考了 Github 開源程式碼 [bioma-tcn-ae](https://github.com/MarkusThill/bioma-tcn-ae) 以及其文獻 -- 基於以下論文的用於時間序列異常檢測的（基線)  

時間卷積神經網路 -- 自動編碼器（TCNAE）的最小工作示例：

Thill, Markus; Konen, Wolfgang; Bäck, Thomas (2020)
[Time Series Encodings with Temporal Convolutional Networks Inproceedings](http://www.gm.fh-koeln.de/ciopwebpub/Thill20a.d/bioma2020-tcn.pdf)
In: Vasile, Massimiliano; Filipic, Bogdan (Ed.): 9th International Conference on Bioinspired Optimisation Methods and Their Applications (BIOMA), Bruxelles.

## Awarded to the persons in recognition of the best papers in the 8th International Conference on Advanced Technology Innovation 2023
![IMG_0031](https://github.com/user-attachments/assets/20fe9d1a-6c33-4207-af70-805622296f8c)


**注意事項 ：使用 SE-TCNAE 進行齒輪缺陷診斷與分類任務，此為論文專案如需使用必須經過本人同意。**

**如須引用請寄信至 iinoshirozheng@gmail.com 訊問。**
