# tiny-wechat-robot
使用 code hijack 和 code injection 来实现一个简单的微信机器人应用。

## usage:
1. start the static http server `node http_static_server.js`
2. run `phantomjs phantomjs_wechat.js`
3. 扫码登陆微信

Tested with `phantomjs v2.1.1` and `node v7.7.3`

## 核心功能
目前就是一个最简化的`ping-pong`应答机器人: 
1. 收到`ping`，回复`pong`；
2. 收到`pingping`，回复`pongpong`；
3. 收到`pingpingping`，回复`pongpongpong`；