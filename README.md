# Identifying-Pulse-through-Skin-Tone-Changes
## 目錄
---
## 研究設備 Research equipments
* Macbook Pro M2
* 高登心率儀(WowGoHealth Heart Rate Monitor)
* 圓剛PW313 Live Streamer CAM
---
## 環境與模組
* Python: 3.9
* IDE: VS Code
* Object detection: [YOLOv8](https://github.com/ultralytics/ultralytics)
* Skin detection: [deepgaze](https://github.com/mpatacchiola/deepgaze)
### 環境安裝
1. 創建一個新的虛擬環境，並使用 Python 3.9。(使用的是Anaconda)
    ```
    conda create --name <environment_name> python=3.9
    ```
2. 開啟環境並安裝
   ```
   conda activate <environment_name>
   ```
3. 用pip安裝文件中的所有套件
   ```
   pip install -r packsges.txt
   ```
