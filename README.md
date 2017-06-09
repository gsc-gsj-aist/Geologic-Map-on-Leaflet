# Geologic-Map-on-Leaflet
メタ情報の表示機能をもつ、20万分の1シームレス地質図閲覧のためのJavascriptソースコードの例 

*概要*  
地図描画用のライブラリ（Leaflet）に、改良版のL.TileLayer.BetterWMS.jsを組み合わせ、GetFeatureInfo機能を持つ地質図幅閲覧用のビューアーを構成します。この機能により、地質画像上をクリックすると、全国任意の場所の地質情報がポップアップ画像として得られます。
本ソースコードの実行には、以下のオープンソースライブラリを必要とします。利用に際しては、各ライブラリのライセンスに従ってください。 

・Leaflet (BSD License)  
・jQuery (MIT License)  
・Proj4js (MIT License)  
・L.TileLayer.BetterWMS.js (https://github.com/gsc-gsj-aist/Leaflet-GetFeatureInfo) 
