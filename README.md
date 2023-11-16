# Weather station

NB: Personal project

Esp32 with rust

## IOT stuff

- Azdelivery devkit v4
- waveshare epd 2.13 (revision 2.1)

[Datasheets](./medias/)

## Schema

| EPD  | ESP32 GPIO |
| ---- | ---------- |
| VCC  | 3.3V       |
| GND  | GND        |
| DIN  | MOSI(23)   |
| CLK  | SCK(18)    |
| CS   | SS(5)      |
| DC   | 17         |
| RST  | 16         |
| BUSY | 4          |

## Dependencies

Warning

- (2023/11/18): epd waveshare 0.5 not compatible with 0.8 embedded graphics lib
