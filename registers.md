| Регистр | Кол-во | Функция | Название | Тип значения | Тип поля | Порядок байт | Ед. | Опрос |
|---|---|---|---|---|---|---|---|---|
| 0 | 1 | 01 | Common Alarm | UNSIGNED | bit | be | — | 1m |
| 2 | 1 | 01 | Common Shutdown | UNSIGNED | bit | be | — | 1m |
| 6 | 1 | 01 | Mains On-load | UNSIGNED | bit | be | — | 1m |
| 7 | 1 | 01 | Gen On-load | UNSIGNED | bit | be | — | 1m |
| 8 | 1 | 01 | Emergency Stop | UNSIGNED | bit | be | — | 1m |
| 41 | 1 | 01 | In Auto Mode | UNSIGNED | bit | be | — | 1m |
| 42 | 1 | 01 | In Manual Mode | UNSIGNED | bit | be | — | 1m |
| 43 | 1 | 01 | In Stop Mode | UNSIGNED | bit | be | — | 1m |
| 48 | 1 | 01 | Emergency Stop Input | UNSIGNED | bit | be | — | 1m |
| 65 | 1 | 01 | Mains OK | UNSIGNED | bit | be | — | 1m |
| 72 | 1 | 01 | Gen OK | UNSIGNED | bit | be | — | 1m |
| 0 | 1 | 03 | Mains Ua | UNSIGNED | uint16 | be | V | 1m |
| 1 | 1 | 03 | Mains Ub | UNSIGNED | uint16 | be | V | 1m |
| 2 | 1 | 03 | Mains Uc | UNSIGNED | uint16 | be | V | 1m |
| 3 | 1 | 03 | Mains Uab | UNSIGNED | uint16 | be | V | 1m |
| 4 | 1 | 03 | Mains Ubc | UNSIGNED | uint16 | be | V | 1m |
| 5 | 1 | 03 | Mains Uca | UNSIGNED | uint16 | be | V | 1m |
| 6 | 1 | 03 | Mains Frequency | FLOAT | uint16 | be | Hz | 1m |
| 7 | 1 | 03 | Gen Ua | UNSIGNED | uint16 | be | V | 1m |
| 8 | 1 | 03 | Gen Ub | UNSIGNED | uint16 | be | V | 1m |
| 9 | 1 | 03 | Gen Uc | UNSIGNED | uint16 | be | V | 1m |
| 10 | 1 | 03 | Gen Uab | UNSIGNED | uint16 | be | V | 1m |
| 11 | 1 | 03 | Gen Ubc | UNSIGNED | uint16 | be | V | 1m |
| 12 | 1 | 03 | Gen Uca | UNSIGNED | uint16 | be | V | 1m |
| 13 | 1 | 03 | Gen Frequency | FLOAT | uint16 | be | Hz | 1m |
| 14 | 1 | 03 | A Phase Current | UNSIGNED | uint16 | be | A | 1m |
| 15 | 1 | 03 | B Phase Current | UNSIGNED | uint16 | be | A | 1m |
| 16 | 1 | 03 | C Phase Current | UNSIGNED | uint16 | be | A | 1m |
| 17 | 1 | 03 | Water Temperature | UNSIGNED | uint16 | be | °C | 1m |
| 19 | 1 | 03 | Oil Pressure | UNSIGNED | uint16 | be | kPa | 1m |
| 21 | 1 | 03 | Fuel Level | UNSIGNED | uint16 | be | % | 1m |
| 23 | 1 | 03 | Engine Speed | UNSIGNED | uint16 | be | RPM | 1m |
| 24 | 1 | 03 | Battery Voltage | FLOAT | uint16 | be | V | 1m |
| 25 | 1 | 03 | D+ Voltage | FLOAT | uint16 | be | V | 1m |
| 26 | 1 | 03 | Active Power | UNSIGNED | uint16 | be | kW | 1m |
| 27 | 1 | 03 | Reactive Power | UNSIGNED | uint16 | be | kvar | 1m |
| 28 | 1 | 03 | Apparent Power | UNSIGNED | uint16 | be | kVA | 1m |
| 29 | 1 | 03 | Power Factor | FLOAT | uint16 | be | — | 1m |
| 30 | 1 | 03 | Maintenance Countdown (h) | UNSIGNED | uint16 | be | h | 1m |
| 31 | 1 | 03 | Maintenance Countdown (min) | UNSIGNED | uint16 | be | min | 1m |
| 32 | 1 | 03 | Battery Pack Voltage | UNSIGNED | uint16 | be | V | 1m |
| 43 | 3 | 03 | Engine Runtime | UNSIGNED | uint16 | be | uptime | 1m |
