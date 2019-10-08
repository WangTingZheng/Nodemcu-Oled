[![Build Status](https://travis-ci.com/WangTingZheng/Nodemcu-Oled.svg?branch=master)](https://travis-ci.com/WangTingZheng/Nodemcu-Oled)
# 硬件
- nodemcu
- oled 0.96inch I2C
# 连接
- SDA ==> D1（5）
- SCL ==> D2（4）*您也可以在文本中找到“SDC”
- VCC ==> SSD1306可以直接从NodeMCU模块用5V（外部）或3.3V供电。
- GND ==> GND
# 添加头文件路径
在`.vscode/c_cpp_properties.json`内添加
```JSON
 "includePath": [
        "./lib/esp8266-oled-ssd1306/src",
        ""
  ],
```

# 图像库
- [SSD1306](https://github.com/ThingPulse/esp8266-oled-ssd1306)#   N o d e m c u - O l e d  
 