G06 有至誠之目，則有善術
======================

成員：簡郁展、潘立恆、邱繼賢、陳暘、劉慧新


## 題目

From @JoeBiden to @POTUS


## 連結

<!-- 請記得修改下方的相對路徑及連結 -->

- [投影片](./G06_slides.pdf)
- [書面報告](./G06_report.pdf)  
- [專案網站](https://sevenpray.github.io/2021R_biden_report/Biden-POTUS-Final-Project.html)



<!-- 下方內容為說明用途，繳交時請將其刪除 -->

-------

小組期末專案繳交說明
=======================

## 繳交方式

每組請**指派一位組員**，至 <https://classroom.github.com/a/DKdjX9ut> 接受作業邀請 (方式同個人作業繳交)。領取之後，請**務必**填寫此 [google 表單](https://forms.gle/ZEUTEi3GJdenJutg6)。之後的任何檔案上傳及更新，請透過**這位組員**的帳號進行。

#### 期限

請於 **2021-06-24 17:59** 前完成所有項目的上傳 (遲交不予計分)。


## 小組資訊

領取作業後，請在最上方的標題寫下組別 (e.g. `G01`) 以及組名，並在標題下方寫下組員姓名。組別與組名對照，見下表：

![組別與組名對照](https://img.yongfu.name/rlads/2021GID.png)


## 繳交項目

- [ ] 原始碼及數據 (必要)
    - 建立一個**資料夾** `src/`，將所有 Rscript、相依檔案 (例如，原始資料) 以及數據 (分析產出之資料) 置於 `src/` 內
    - `src/` 內的檔案結構請自行決定，但**其內必須有一個 `README.md`**，用以簡要說明每個 Rscript 的功用以及產出之資料的內容
    (`src/README.md` 即是原始碼的說明文件)
    - 注意：若資料的**大小超過 100MB**，請勿將其上傳至 GitHub (GitHub 不會讓你上傳)。請另外將資料上傳到其它地方 (e.g., 雲端硬碟) 再於 README.md 內提供下載連結。
- [ ] 書面報告 (必要)
    - 檔名：`G<組別>_report` (例: `G01_report.pdf`)，請將此檔案放在此 repo 根目錄
    - 格式：`.pdf`
    - 書面報告的最後，請附上組員的工作分配表
- [ ] 投影片
    - 檔名：`G<組別>_slides` (例：`G01_slides.pdf`)，請將此檔案放在此 repo 根目錄
    - 格式：`.pdf` (如果是其它檔案格式，如 `.pptx`，請先轉換成 PDF 檔再放上來)
- [ ] 其它相關內容 (e.g., 專案網站、Shiny App 等) 請以**連結**的方式，放在這份 README.md 的 `## 連結` 部份


### 期末專案範例

若仍不清楚 repo 結構的規定或對如何組織 `src/` 沒有頭緒，可參考 [TA 示範專案](https://github.com/rlads2021/TA-project)。


## 參考模板

原則上，投影片以及書面報告的製作方式並無限制 (但最後檔案需轉換成 PDF 檔)。有興趣的同學可以使用 R Markdown 撰寫書面報告與製作投影片。R Markdown 非常適合用於這個情況，因為它可動態插入程式執行的結果，所以若製作報告過程中，發現需要修改程式碼，就不須重新輸出圖片、再將其插入檔案之中。同學可以參考 [pagedown](https://github.com/rstudio/pagedown) 的[書面報告模板](https://github.com/rlads2021/TA-project/tree/main/src/report)。
