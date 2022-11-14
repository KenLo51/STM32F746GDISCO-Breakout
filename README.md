# Breakout Game With Simple Physical Simulation and Collision on STM32

##### 基本功能：
>  1. 按下USR鍵後，遊戲開始。
>  2. 發球時需使用隨機方式產生四個斜角的發球角度，發球位置為螢幕中心。
>  3. 球的移動速度為10ms，移動1個X/Y pixel
>  4. 螢幕中間上方需有計分顯示。
>  5. 用手指拖移反彈板，可將球反彈。
>  6. 螢幕上、左、右邊緣，也可將球反彈。
>  7. 當球接觸到磚塊後，磚塊消失，並將球反彈。
>  8. 當反彈板沒接球到時，螢幕中心顯示”Game Over”，全部磚塊都被打完，螢幕中心顯示”Win”，遊戲結束並且計時停止。

##### 改進功能：
>  1. 發球時需使用隨機方式產生任意斜角的發球角度，同時避免過於角度水平。
>  2. 反彈板依據擊球位置改變反彈角度。
>  3. 增加磚塊四角的不同角度碰撞。

##### 使用環境：
>  1. STM32CubeMX Version 6.4.0
>  2. µVision V5.36.0.0
