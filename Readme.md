# Zephyr manifest for 6TRON boards

## Usage
- Initialize the Zephyr workspace
```bash
west init -m https://github.com/catie-aq/zephyr_manifest zephyr_6tron_workspace
```

- Update the Zephyr workspace
```bash
cd zephyr_6tron_workspace
west update
```

## Supported boards

### Zest Core
- [Zest Core STM32L4A6RG](https://catie-aq.github.io/6tron_www/zest_core_stm32l4a6rg/)

### Zest
- [Zest Sensor IMU](https://catie-aq.github.io/6tron_www/zest_sensor_imu/)