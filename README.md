# homeassistant-airpurifierProH

支持小米空气净化器proH，可能也支持小米空气净化器3。

第一次做插件，代码可能写得不是很好，请各位大神多多指教

configuration.yaml内添加
fan:
  - platform: xiaomi_airpurifierProH
    name: Bedroom Airpurifier
    host: 192.168.50.213
    token: aaf606fa89c66192f91158a37e22fdfe
    
其实token貌似没有用到，所以不需要真实的token也行

services.yaml文件好像没起作用，正在学习。
