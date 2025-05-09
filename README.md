# STM32G4xx Cell DevBoard开发板

一时兴起无聊做的STM32G4开发板（因为G474/G431两个芯片pin2pin兼容所以在上面加了个丝印区分，应该是通用的吧），称之为Cell是因为这玩意确实比较小巧，目前功能如下：

- 25MHz HSE晶振，32.768KHz LSE晶振
- USB Type-C接口（占用PA11，PA12）
- 0.91寸SSD1306 128x32 OLED显示屏，OLED使用PB8（SCL），PB9（SDA）作为引脚，而PB8与BOOT0复用，使用前需要在STM32CubeProgrammer修改Option Bytes
- TPS54302降压供电，最高支持28V输入电压，最大电流为2A（受制于电感

后面应该会基于这个板子设计底板。

### 目前已经打样验证，可放心使用

![OLED](/Pictures/IMG_20250510_000536.jpg)

![两块板子](/Pictures/IMG_20250510_000611.jpg)
