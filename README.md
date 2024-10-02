### 1. 簡介 (Introduction)
農產品拍賣價格可透過網站獲得，但因格式無法有效被使用，故透過ETL使資料可視覺化。
 The commodity auction price can be downloaded from the public website of the government, but that format cannot be directly used for analysis. Thus, we processed these data by ETL to make visualization easily.
### 2. 工具 (Tools)
* Python for ETL
* MS Power BI for data visualization
### 3. 流程 (Process)
* 資料清洗 (ETL process): 將原有格式重新整理，並使資料處理分為首次與新增 (Tiding and reforming the raw data, and the data processing includes first time processing and continuous adding)
* 商品價格儀錶板 (Dashboard of Commodity Price): 將處理後資料進行視覺化，以利速覽價格與商品資訊 (Visualizing processed data by Power BI, and then it can be easy to read and search information of commodity and price)  
### 4. 處理後資料 (Processed Data)
* 商品資料 (Commodity List)
  每日交易價格 (Daily Trading Price)
* 市場代號 (Market No. List)
### 5. 備註 (Remark)
* 原始資料來源 (Raw data from https://amis.afa.gov.tw/veg/VegProdDayTransInfo.aspx)
* 時間區間 (Period) : 2023/01/01~2024/4/28
* 細節可參考該論文 (detailed explanation refer to https://hdl.handle.net/11296/6jr667)
