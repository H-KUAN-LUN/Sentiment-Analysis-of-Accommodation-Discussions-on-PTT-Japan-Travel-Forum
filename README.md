# PTT日本旅遊板住宿資料分析  
分析PTT論壇上的日本旅遊板關於住宿的文章進行情緒分析  
用Python進行資料清洗、處理和視覺化，瞭解關於日本旅遊住宿文章討論趨勢和情感傾向

## 資料來源  
透過爬蟲取得PTT日本旅遊板住宿相關文章  
筆數：865

## 使用函式庫  
* pandas
* matplotlib
* wordcloud
* jieba
## 情緒分析結果  
可以看到隨著2022年9月疫情政策開始逐步調整鬆綁日本旅遊板上正面以及負面情緒的文章數開始不斷提升  
且正面情緒的文章數量遠高於負面情緒  
![method](https://raw.githubusercontent.com/HUAN-LUN/Sentiment-Analysis-of-Accommodation-Discussions-on-PTT-Japan-Travel-Forum/main/result/output.png)

## 情緒代表字  
![圖片失效](result\情緒代表字.png)  
## 情緒分數趨勢折線圖
![圖片失效](result\情緒分數趨勢折線圖.png)
## 文字雲
![圖片失效](result\文字雲.png)  
## 京都討論聲量高 因此查看一下關於京都的正向情緒字詞
![圖片失效](result\京都正向情緒字.png)
## 舒適看起來是用來形容住宿環境 查看含有京都以及舒適的文章原文  
![圖片失效](result\京都舒適原文.png)

