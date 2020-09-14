請完成一個client/server的猜數字GAME，

雙方先選定一個1至100的數字。server由亂數決定。

每回合client輸入一個猜測的值，server回覆過大/過小/猜中。

server也會猜一個數，client回覆過大/過小/猜中。

誰先猜中對方的數字，會顯示誰勝利，程式結束。

server請用Binary Search Algorithm來猜。

範例輸出：

client畫面：

回合1：請輸入猜的數字：49

server說太大。server猜50。請回覆：too small

回合2：請輸入猜的數字：20

server說太小。server猜75。請回覆：too small

回合3：請輸入猜的數字：30

server說太小。server猜87。請回覆：too large

回合4：請輸入猜的數字：40

server說你猜對了。



server畫面：

回合1：client猜49，too large。server猜50。

回合2：client猜20，too small。server猜75。

回合3：client猜30，too small。server猜87。

回合4：client猜40，get answer。