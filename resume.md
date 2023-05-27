## 物联网嵌入式开发
- **硬件**:
    ESP8266单片机、MX25L12835E存储、ssd1306显示屏
- **开发流程**：
    1. 使用C＃开发工具开发上位机（串口连接工具），以便自定协议传输字库文件到esp8266连接的MX25L12835E存储中
    2. 使用ESP32的RTOS包完成esp8266的IIC驱动显示屏与MX25L12835E的驱动,并实现wed配网功能。
    3. 使用android开发手机APP，并通手机MQTT协议实现ESP8266显示与点灯等功能

- #### 物联网的示例演示
![](https://cdn.jsdelivr.net/gh/praybb/praybb.github.io/blog//esp8266.jpg)
下图为个人开的天气查询与扫码程序的开发，其中也加入mqtt的发送与接收，在此只截取部分功能。
![](https://cdn.jsdelivr.net/gh/praybb/praybb.github.io/blog/android.jpg)
