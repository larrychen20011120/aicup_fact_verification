# aicup_fact_verification
AI CUP 2023 事實文字檢索與查核競賽 

## 所需套件
```
pip install -r requirements.txt
```
如果在 colab notebook 就執行下載的 block 即可

## 環境
* Google Colab
* 如需訓練請開啟GPU（實作時為T5）

## 執行前
* 首先確定 data 底下的 wiki-pages 資料夾下有比賽的資料 (下載:https://drive.google.com/drive/folders/1kpxgrnE60BaIkqksfvkDYFdAesItN-Sd?usp=drive_link)
* **aicup_full_pipeline.ipynb** 是三個步驟的完整筆記本
* 名稱中有 utils 的 python 檔案主要是用來做資料格式轉換處理的
* analysis.ipynb 是分析模型在不同類別表現的檔案
* tfidf.ipynb 是用 tfidf 方法時做檢索的程式
* dict.txt.big 是結巴斷詞的字典

## 復現
根據報告中設定的參數填入`aicup_full_pipeline.ipynb`的參數欄位即可復現，原筆記中的參數可能有些不同。

## 最終參數下載連結
* [**sentence retrieval**](https://drive.google.com/file/d/12W9Vhax-BpAFs3IlskmfGX1Hue1zgLLq/view?usp=sharing)
* [**claim verification**](https://drive.google.com/file/d/102AJC2GrVCAuN1_WpMzB3ok6aVMULuaI/view?usp=sharing)

## 完整檔案連結
可到[這裡](https://drive.google.com/drive/folders/1UUTz96u3nvCCOCba4Ui85On6tBCdK5c2?usp=sharing)查看
