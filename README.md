# Python+ESP32驱动LED Matrix展示Spotify专辑封面

该程序被设计为两个部分，ESP32开发板作为MQTT Client订阅数据流，另外需要在计算机中运行调用Spotify接口的程序同时作为MQTT Client发布者，可打包成桌面端应用。当Spotify中播放音乐时，LED Matrix即可展示专辑封面，并可同步自动切换。

## Spotify API:

https://developer.spotify.com/documentation/web-api/

## 示例：

![ChessUrl](https://p78.f0.n0.cdn.getcloudapp.com/items/kpu8WGP2/c1189bac-9caa-4fc9-a94f-fb72cf505813.jpg?source=viewer&v=ed2bf248e8cb6451f13edbdfbd806a44)

![ChessUrl](https://p78.f0.n0.cdn.getcloudapp.com/items/jkuXWNWk/5746976c-bb6e-49bc-a8f0-d2b144ff7c29.gif?source=viewer&v=a3b7c5403aa8d57f570aa2bcf7816ea0)

## ESP32开发板和LED Matrix：

![ChessUrl](https://p78.f0.n0.cdn.getcloudapp.com/items/Qwund1x5/be0198a5-9855-487f-8266-c36c9f19ec10.jpg?source=viewer&v=37602c50df36947e155878ea0cbfe2c2)

![ChessUrl](https://p78.f0.n0.cdn.getcloudapp.com/items/nOuXbyE7/f66a8ba8-1fd8-4aff-bb85-b584099bdacf.jpg?source=viewer&v=eb1ed376a1a01f3ed0f92dad26a501e0)

## 参考资料：

https://github.com/2dom/PxMatrix

https://github.com/mrfaptastic/ESP32-HUB75-MatrixPanel-I2S-DMA