# Arduino Sensor Projects

This repository contains two separate Arduino projects demonstrating sensor integration:

## 1. IMU Sensor (BMI270 + BMM150)

- Uses the `Arduino_BMI270_BMM150` library
- Reads acceleration data along X, Y, and Z axes
- Prints the acceleration values to the Serial Monitor every 500 ms

**Folder**: `imu_sensor`

**File**: `imu_sensor.ino`

## 2. HS300x Temperature & Humidity Sensor

- Uses the `Arduino_HS300x` library
- Reads temperature (°C) and humidity (%)
- Prints the readings to the Serial Monitor every 2 seconds

**Folder**: `hs300x_sensor`

**File**: `hs300x_sensor.ino`

---

## How to Run

1. Install the required libraries in the Arduino IDE:
   - **Arduino_BMI270_BMM150**
   - **Arduino_HS300x**

2. Connect your sensors to the Arduino according to their datasheets.

3. Open each `.ino` file in the Arduino IDE and upload to your board.

4. Use the Serial Monitor at **9600 baud** to see the readings.

---

## Repository Structure

