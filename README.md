# Chinese_Dark_Chess

這是一個懂得下暗棋的智慧玩家，棋力非常一般。
面對隨機性玩家可以達到高達6成的勝算。

人工智慧課的老師讓我們寫暗棋對弈的智慧Agent。寫了好幾周總算完成了雛形，以下是這支程式的一些説明：
做到了:
1. Alpha-Beta Pruning （5步）
沒做到：
1. 沒有對子節點做優先排序加强Alpha-Beta Pruning的效益
2. 完全不考量關閉的棋子 （ 非不得已不走 ）

Bug:
程式會反復在小區内移動，沒有對重複動作這件事做防呆。

注：
權重方面參考 =》 https://github.com/kuruwa2/Dark-Chess-AI/tree/master/code
產生節點的方法原本很複雜，今天下午被 黃嘉佑 學長提了一提，便直接參考原程式的expand function。
