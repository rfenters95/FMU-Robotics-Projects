# Project-2

## Goals
- Read the **Wall Signal** Sensor, and map it's value to the __Power LED Color__ value
of the **LED** command. <br> **Hint: mapping will not be 1-to-1**.

- Read the **Bump** Sensor. Given the response respond as follows:
	- If **both** sensors are pressed, then drive straight backwards until sensors are deactivated.
	- If **one** sensor is pressed, then drive away from the activated sensor with an **ICC = 1m** until <br>
the sensor is deactivated.

## How to execute
  1. Navigate to _main.c_
  2. Right click "open in terminal"
  3. `make serial && sudo ./serial`
