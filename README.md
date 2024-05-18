# Identifying-Pulse-through-Skin-Tone-Changes
# 透過膚色變化辨識脈搏
## 目錄
---
##研究設備 研究設備
* Macbook Pro M2
*高登心率儀(WowGoHealth Heart Rate Monitor)
*圓剛PW313 直播攝影機
---
## 環境與模組
* Python：3.9
* IDE：VS程式碼
* 物體偵測：[ YOLOv8 ] ( https://github.com/ultralytics/ultralytics )
* 皮膚檢測：[ deepgaze ] ( https://github.com/mpatacchiola/deepgaze )
### 環境安裝
1. 建立一個新的虛擬環境，並使用Python 3.9。
    ````
    conda create --name <環境名稱> python=3.9
    ````
2. 開啟環境並安裝
   ````
   conda activate <環境名稱>
   ````
3. 用pip安裝檔案中的所有套件
   ````
   pip install -r packsges.txt
   ````
