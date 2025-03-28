# 距離感應互動裝置

## 功能描述
1. 使用超音波距離感測器測量距離。
2. 當距離小於10公分時：
   - LED燈亮起。
   - 伺服馬達轉動到90度。
3. 當距離大於10公分時：
   - LED燈熄滅。
   - 伺服馬達回到0度。

## 所需材料
1. Arduino UNO x 1
2. USB Cable Cord Type A-Male to B-Male x 1
3. LED x 1
4. 1KΩ電阻 x 1
5. 伺服馬達 (Servo Motor) x 1
6. HC-SR04超音波距離感測器 x 1
7. 杜邦線若干
8. 麵包板 x 1

## 硬體連接
1. **LED**：
   - 正極接 Arduino 的數位引腳 3。
   - 串聯 1KΩ 電阻後接 GND。
2. **伺服馬達**：
   - 信號線接 Arduino 的數位引腳 4。
   - VCC 接 5V，GND 接 GND。
3. **超音波距離感測器**：
   - VCC 接 5V。
   - GND 接 GND。
   - Trig 接 Arduino 的數位引腳 5。
   - Echo 接 Arduino 的數位引腳 6。