### WordWinner
### 简介
单词王者，一个在线答题对战游戏。  
要在4个选项中选出正确的单词汉译，每个问题只有5秒钟，一旦选择便无更改，超时或者答错都算失败。  
### 服务端技术
服务端使用单线程 I/O 多路复用模型。  
通过时间轮管理定时事件。  
使用 JSON 作为数据交换格式。  
使用Redis 存储。  
利用单例模式封装对数据库的操作。  
使用 std::map 和 std::function 避免繁琐的 if-else。  
采用柔性数组减少内存空间的浪费。  
