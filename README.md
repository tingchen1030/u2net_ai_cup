
1. 建置好新環境並切換到檔案路徑下後輸入以下指令可快速安裝套件
```
pip install -r requirement.txt
```

2. pretrain model 可去以下的google 雲端連結下載 [**GoogleDrive**](https://drive.google.com/file/d/1D1eeuuwbccx86rosb1DuWnRRDjwySaC9/view?usp=sharing) 

3. 訓練模型 <br/>
(1)在u2net_train.py的這隻程式中的53行位置可修改train image 和 mask label image 的位置<br/>
(2)在程式碼的第109行可設定要使用的預訓練model<br/>
```
python u2net_train.py
```
4. 測試模型 <br/>
(1)在u2net_test.py的這隻程式中的62~64行處可選擇要進行預測的影像路徑、預測結果存取路徑和預測所使用之模型檔案<br/>
(2)在程式碼的第109行可設定要使用的預訓練model<br/>
```
python u2net_test.py
```