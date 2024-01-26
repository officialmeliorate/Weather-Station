Weather Station using esp8266 measures atmospheric temperature, humidity, pressure, rain level indication and displays lively on LCD display and provides a real-time data visualization through the Blynk cloud platform.
In this project we are using esp8266 nodemcu, dht11 temperature and humidity sensor, bmp180 pressure sensor, rain sensor and 16*2 lcd display.

Note:
Since bmp180 is developed by Bosch, they used I2C communication in it. 16*2 LCD display also follows I2C communication. So at a time, we cannot use both these. If you want to include pressure value, comment the lcd code and uncomment the pressure code. 
