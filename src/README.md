# 原始碼說明文件
* `data/`: @JoeBiden與@POTUS之推文資料，詳見其內之 [README.md](./data/README.md)
* `Biden-POTUS-Final-Project_files/`: 專案相關圖表檔案
* `site_libs/`: 網站所需之相關資源 (e.g., jquery, fonts)
* `Biden POTUS Final Project.Rmd`: 程式碼
* `Biden-POTUS-Final-Project.html`: Rmd輸出之html檔
* `style.css`: Github Pages 之css格式設定
* `_site.yml`: Github Pages 相關設定 

要將 Rmd 輸出成 html 請執行：

```r
rmarkdown::render_site("Biden POTUS Final Project.Rmd")
```
