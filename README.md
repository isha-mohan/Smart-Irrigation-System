# Smart-Irrigation-System
Smart low-cost irrigation system using Arduino UNO, YL-69 soil moisture sensor, submersible dc water pump, HC-05 bluetooth module(additional)  

# **Abstract**
The project describes smart irrigation system using the concepts of Internet of Things. The system consists of an arduino which is the microcontroller and controls a 5V semi- submersible water pump according to the water level in the soil. The system also consist a bluetooth module that can be used to connect the user’s mobile application to the system. The user can receive sensor data values over the bluetooth using mobile application. The system automatically turns the water pump on when the moisture level in the soil is very low and turns the water pump off when the moisture level reaches the threshold value. 
# **Area of utility**
- The primary focus of this project is to help the farmers and reduce their work.

- This project can be implemented in perennial plant irrigation land and gardening land.
# **Hardware components used**
1. **Arduino UNO**

![arduino-uno-r3_5](https://user-images.githubusercontent.com/31012452/33338365-e59758b2-d49b-11e7-8465-f891168a69ff.jpg)

2. **HC-05 Bluetooth Module(OPTIONAL)**

![fc-114](https://user-images.githubusercontent.com/31012452/33338481-359fb1b0-d49c-11e7-91e1-002008457bdb.jpg)

3. **YL-69 soil moisture sensor**

![51vwscqyaxl](https://user-images.githubusercontent.com/31012452/33338563-71db65ac-d49c-11e7-8b5b-5ada72f95089.jpg)

4. **DC Water Pump**

![s-l225](https://user-images.githubusercontent.com/31012452/33338647-bab40dce-d49c-11e7-829a-f1dbd5183376.jpg)

# **Connections**
 1. **HC-05 bluetooth module**

- Vcc to pin 5V of arduino uno

- Ground to pin ground of arduino uno

- Rx to pin 1(Tx) of arduino uno

- Tx to pin 0(Rx) of arduino uno
 2. **YL-69 soil moisture sensor**

- A0 to analog pin 0 of arduino

- GROUND to ground pin of arduino uno

- Vcc to pin 5V of arduino uno
 3. **DC water pump**

- Black wire to ground pin of arduino uno

- Red wire to pin 13 of arduino uno
# **Screenshot of Arduino UNO Serial Monitor**

![screenshot 130](https://user-images.githubusercontent.com/31012452/33339058-ee663330-d49d-11e7-9738-443b0ae7f2c4.png)

![screenshot 129](https://user-images.githubusercontent.com/31012452/33339082-fd7fa4b4-d49d-11e7-8c40-ffe51a726024.png)

# **Android Application(OPTIONAL)**

Android Application can be used to get the sensor values. App can be connected to arduino using bluetooth module. This application is completely optional just like the bluetooth module.
App has to be paired with hc-05 module
Pair key:- 1234 or 0000

![whatsapp image 2017-11-29 at 12 43 50 am](https://user-images.githubusercontent.com/31012452/33339213-7c78f6bc-d49e-11e7-9f37-4cb1cf897eb0.jpeg)



