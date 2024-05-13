[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/X3WkcXtG)  
找20張左右想要訓練的對象  
然後使用https://www.birme.net/?target_width=512&target_height=512將其裁剪成512*512的大小。  
這會是訓練圖的Dataset  
使用相同的網站裁減規範圖，需要與訓練圖相似但又不能一樣，大概需要100張。
這會是規範圖的Dataset
用Dataset_Maker將兩者的提示詞標記好 然後適當的刪除一些提示詞  
然後就用Lora訓練那些資料

這次作業是跟著https://vocus.cc/article/642db062fd897800014596ad 的步驟做的
