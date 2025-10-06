# Home Assistant Modbus configuration files for Airobot L5
This repository contains files for Home Assistant Modbus configuration for Airobot L5 device (https://airobothome.com/products/airobot-l5/). It could be that the configuration also works for other Airobot ventilation devices.
Currently, only the sensor data reading is included in the setup.

- `configuration.yaml` contains basic device configuration
- `airobot_modbus_sensors.yaml` contains sensor configuration.

## Setup

I used Studio Code Server (https://github.com/hassio-addons/addon-vscode) to edit the configuration files.

- Append contents of [`configuration.yaml`](configuration.yaml) to the HA configuration file `config/configuration.yaml`
- Copy file [`airobot_modbus_sensors.yaml`](airobot_modbus_sensors.yaml) to the HA configuration directory `config`.
