# microbit-battery
microbit-battery

Check micro:bit Battery Status without additional hardware

Let's create an HTML5 Web Bluetooth app to check the battery status without additional hardware. The reading might not be accurate, it is just for demonstration and learning only.

From the ADC reading, it will determine the status based on the following criterias:
1. Battery voltage ~2V, reading is 256
2. Battery voltage ~2.5v, reading is 512
3. USB power, reading is 768

Source code:
https://github.com/ferrygun/microbit-battery/
The code is based on https://os.mbed.com/teams/microbit/code/microbit-battery-test/



