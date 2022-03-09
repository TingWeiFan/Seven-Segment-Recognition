# Seven-Segment-Recognition
此專案的目的是辨識面板上的數字，因此參考了下面連結中的做法，並從中修改了些地方來實現專案的需求。  
https://github.com/jiweibo/SSOCR

## 辨識流程
為了降低辨識數字演算法的出錯率，我先使用YOLOv5找出數字的區域，如下圖  
<img src="img/test15_1.png" width="30%"/>

將數字區域剪裁之後，執行辨識演算法得到結果，如下圖  
<img src="img/test15_1.png" width="30%"/>
