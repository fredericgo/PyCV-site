TechTree 功能規格

概述

TechTree 是一個用網狀圖把程式範例陳列出來的網站，藉著把

這樣陳列程式範例的目的在於，讓新手可以 Learn by example，透過逛一逛地圖快速地掌握社群已經寫好的程式範例。此外老手也能以最高的速度認清社群目前的技術極限，並且致力於向外拓展。





User Story

大象先生是一個軟體工程師，平常都用可恥的 Visual Basic 語言寫程式接案，有一天他在逛臉書時，偶然間看到朋友被標註在一個電腦視覺社團聚會的照片裡，好奇之下連到聚會的網站上，打開了 TechTree，隨便按了一個節點就顯示出如上圖的畫面，由於他跟 Github 不熟，所以按了 download .zip 把程式下載下來玩，但是由於他沒有裝 python 和 opencv 環境，於是發現打不開所以就放棄探索了。需要增加指示引導沒有安裝環境的使用者!!



TechTree行為

地圖的移動與縮放

縮放應該像 Google Map 一樣用滾輪針對滑鼠所在的位置縮放，但要滑順一點佳
按地圖上空白處不放，四處拖曳即可平移

選取一個節點時，右側跳出 markdown 說明，並且自動把地圖視窗移到以該節點為中心處


節點

節點的大小可以決定於
被其他節點參考的次數
被按讚的次數 (?)
下載次數

瀏覽過的節點應該要變色
被選取的節點其說明文字與節點本身都應該變比較明顯

節點考慮以縮圖代表
節點也可以拉動

資源

大量的 d3.js 範例 bl.ocks.org
d3.js 範例: 可以放大、平移、拉扯的網狀圖,一個類似的圖。
Python相關的套件，可以直接挖掘一個script的相依：
modulegraph：https://pypi.python.org/pypi/modulegraph/
Python其實有內建一個模組modulefinder:http://blog.rtwilson.com/how-to-find-out-what-modules-a-python-script-requires/

# PyCV-site
