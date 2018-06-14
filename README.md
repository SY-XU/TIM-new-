# TIM-new-
基于Spring mvc,web socket,mybatis为主要技术，数据连接采用druid，前端主要采用JQuery。 新增了websocket文件传输功能，利用hash实现断点续传。
config中可以修改保存地址
传输队列仍在调试，会报java.io.EOFException: The client aborted the connection.
主要是因为读取不同类型文件判断读到文件尾时会出错，导致ws关闭不正常
调试ing
项目告一段落，专心考研了
