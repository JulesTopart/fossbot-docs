# User Guide

This section will guide you through the steps of assembling, configuring, and using your FOSSBot.

## Assembly Instructions

### Hardware Setup

1. **3D Printing the Parts**: Download the 3D files [here](#) and print them using PETG filament.
2. **Assembling the Electronics**:
   - Attach the **Raspberry Pi Zero** to the main chassis.
   - Connect the **wheel motors**, **gyroscope**, and **accelerometer**.
   - Secure the **LEGO-compatible top cover** and other custom attachments.

### Software Setup

1. **Install Raspbian OS** on the Raspberry Pi Zero.
2. **Install FOSSBot Software**:
   - Clone the repository: `git clone https://github.com/FOSSBot/FOSSBot.git`
   - Follow the setup instructions in the repo to install necessary dependencies.

### First Run

1. **Power up the FOSSBot** by connecting a power source.
2. **Connect to FOSSBot**: Use the web interface or SSH to access the robot.
3. **Calibrate the Sensors**: Run the calibration scripts to ensure accurate sensor readings.

## Controlling the FOSSBot

- **No-coding Mode**: Use the web interface to control basic movements and tasks.
- **Blockly Mode**: Create programs by dragging and dropping blocks in the [Blockly Editor](#).
- **Python Mode**: Use the [Monaco Editor](#) for more advanced control using Python.

### Troubleshooting

- **Motor issues**: Ensure proper wiring and connection to the Raspberry Pi.
- **Sensor calibration**: Rerun the calibration scripts if sensor readings are inaccurate.
