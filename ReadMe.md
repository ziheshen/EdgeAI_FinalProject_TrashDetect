# 垃圾分類物件偵測
## 環境設定
1.  建立python虛擬環境
    ```
    python -m venv YOLOv8-env
    ```
2.  啟動並進入python虛擬環境 
    ```
    source YOLOv8-env/bin/activate
    ```
3.  下載程式碼
    ```
    git clone https://github.com/ziheshen/TrashDetect_Inference.git
    ```

## 模型推論
1.  移動至TrashDetect_Inference目錄下
2.  使用VScode打開 ***inference.ipynb*** 根據檔案內容敘述下載所需的檔案
3.  修改model、推論使用的圖片與影片路徑，並全部執行

------------------------------------

## 使用 Intel OpenVINO DL WorkBench推論
可參考 Intel OpenVINO官網提供的安裝流程與使用方法

**安裝方法：** https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/download.html?ENVIRONMENT=DEV_TOOLS&OP_SYSTEM=WINDOWS&VERSION=v_2023_0&DISTRIBUTION=PIP&FRAMEWORK=PYTORCH

**使用方法：** https://docs.openvino.ai/archive/2021.2/workbench_docs_Workbench_DG_Work_with_Models_and_Sample_Datasets.html
