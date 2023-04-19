# kawa-vt
unvtを使った河川系データのベクトルタイル作成練習 
[unvt/nanban](https://github.com/unvt/nanban)を利用して作業。  
 
### 元データ  
[国土数値情報河川データ](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W05.html)  
[国土数値情報流域界・非集水域データ](https://nlftp.mlit.go.jp/ksj/gmlold/datalist/gmlold_KsjTmplt-W12.html)  
[国土数値情報行政区域データ](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-v3_1.html)

### 変換  
Tippecanoe  
- pbf  
--no-tile-compression --no-feature-limit --no-tile-size-limit  

### スタイル
charites

### 目次  
#### 茨城県
url:  
style:
- 河川(平成20年)  
zoom：10-14  
- 流域(昭和52年)  
zoom:10-14
- 行政区域(令和4年)
zoom:10-14



