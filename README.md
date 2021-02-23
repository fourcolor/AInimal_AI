# AI：交友適配程度預測


## 想法

**x_data：假設此模型的feature類似於BIG 5 Model，可以將每個使用者的性格展現出來。那麼input_data就是任意一個人他所聊天過的每個人對應的feature的回覆頻率及聊天句數量**

**y_data:為根據那個人對每個類型的人對應的聊天句數量、回覆頻率作為基準，利用類似softmax函數將他對所有種類型的人做配對分類。**

**dataset:為上述方法將所有相近feature的x_data其對應其他種類feature的Y_data作加總**

## 結論

**藉由這個模型可以評斷出一個使用者他的feature跟哪些feature的人比較合得來**
