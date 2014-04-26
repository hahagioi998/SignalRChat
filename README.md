SignalRChat
===========

SignalR实现的聊天室　    SignalR 是一个asp.net异步库，它提供广播消息到多个client端的机制。 SignalR能用来持久客户端与服务端的连接，让我们便于开发一些实时的应用，例如聊天室在线预订系统，股票交易等实时应用。这可以显著降低服务器的负载确保没有不必要的请求从重复客户端请求。 SignalR是非微软的正式开源项目。  它实现了Long Polling的模式，传统的 AJAX 应用不同之处在于：  1. 服务器端会阻塞请求直到有数据传递或超时才返回。  2. 客户端 JavaScript 响应处理函数会在处理完服务器返回的信息后，再次发出请求，重新建立连接。  3. 当客户端处理接收的数据、重新建立连接时，服务器端可能有新的数据到达；这些信息会被服务器端保存直到客户端重新建立连接，客户端会一次把当前服务器端所有的信息取回。
