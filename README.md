# Hi-Link mmWave Radar For ESPHome

> [!WARNING]
> This repository is **no longer actively maintained** (inactive/archive status).
> Existing content is kept for reference only, and no new feature development is planned.

Suggest used ESP-IDF framework to improve efficiency and stability.  
If using Arduino Framework, disconnecting the UART cable might cause API disconnect errors.

## Supported modules (completed)
- ✅ LD1115H UART/GPIO output, UART with sensitivity adjustable ([Link](./LD1115H))
- ✅ LD1125H UART output, UART with sensitivity adjustable ([Link](./LD1125H))
- ✅ LD112 GPIO output without adjustable settings ([Link](./LD112))
- ✅ LD017 IIC/GPIO output, IIC/GPIO with sensitivity adjustable ([Link](./LD017))
- ✅ LD012 GPIO output with sensitivity adjustable pins ([Link](./LD012))

Code is available in each radar folder.  
Note: Don't use 5V on LD017, LD012, LD2420.

## Similar device mapping
- LD2410 = LD2410B = LD2410C
- CEM5825F = LD1125H
- CEM5855H = LD1115H


## References
- ESPHome:
  - <https://esphome.io/cookbook/uart_text_sensor.html>
  - <https://esphome.io/custom/uart.html>
  - <https://esphome.io/components/uart.html>
  - <https://esphome.io/components/sensor/custom.html>
