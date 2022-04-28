# b4x20220429

B4X實驗: JServer.WebSocket多人聊天室???(B4J)
參考資料:
https://www.b4x.com/android/forum/threads/webapp-chatroom-threads-sessions-and-server-events.39969/#content


1.參考
https://www.b4x.com/android/forum/threads/webapp-chatroom-threads-sessions-and-server-events.39969/#content

2.HTML畫面 引用
https://github.com/codingXiang/simple_chat

3.聊天室兩大重點
ws.Session.HasAttribute("name")
CallSubDelayed3(ChatShared, "NewConnection", Me, name)


4.傳送訊息格式
新訊息: {"msg":"CCCCC","name":"aaa"}

5.心臟機制
pong


0.程式碼的使用
https://github.com/eric19740521/b4x20220429

