# educational-rover-hardware

教育用ローバーのハードウェア仕様

オンボードコンピューターにRaspberry Pi Zero/Wを使用した教育用ローバーの設計書です。

## ピン配置

### DRV8835 (Motor Driver)

| Part/Leg | Raspberry Pi GPIO |
| --- | --- |
| AIN1 | 18 |
| AIN2 | 23 |
| BIN1 | 24 |
| BIN2 | 25 |

### SSD1306 (OLED Display)

| Part/Leg | Raspberry Pi GPIO |
| --- | --- |
| SDA | 2 |
| SCL | 3 |
| VCC | 1 |
| GND | (GND) |

### BMX055 (9 Axes Sensor)

| Part/Leg | Raspberry Pi GPIO |
| --- | --- |
| SDA | 2 |
| SCL | 3 |
| VCC | 1 |
| VCCIO | X |
| 3V3 | 1 |
| GND | (GND) |

### LEDs

| Part/Leg | Raspberry Pi GPIO |
| --- | --- |
| LED1 | 16 |
| LED2 | 20 |
| LED3 | 21 |
