# STM32-大夏龙雀GNSS-安信可ESP8266-WebSocket

STM32F103C8T6关于大夏龙雀GNSS模块驱动开发，同时实现WebSocket服务端向客户端发送校验信息以及发送信息的功能，然后浏览器可以通过WebSocket去实现对单片机发来的信息进行回显，我这里只用了高德的API做地图上显示位置实时信息，后续可能会去完整实现WebSocket服务端，可以进行双向通讯，浏览器前端上位机可以设计更多的一些功能(有时间的话，没有的话就莫得办法了)。