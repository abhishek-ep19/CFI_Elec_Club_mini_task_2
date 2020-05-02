# CFI_Elec_Club_mini_task_2
Ideating upon 2 projects
### [ 1. Raspberry Pi radio](https://www.instructables.com/id/Raspberry-Pi-Radio/)
#### Ideation:
| Hardware parts used   | Replacable By | Feasibility to replace | Advantages | Disadvantages |
| :---:                 | :---:         | :---:                  | :---:      | :---:         |
| Raspberry Pi | ESP32 | Feasible as they can be connected to internet and perform the same functions | They are cheap as compared to Rpi | -- |
| Rotary encoder | Screen display | Not a good option to replace | Currently, very cheap but after replacing we would be having a touch display | Very Costly |
| Audio amplifier | -- | Not a good option to replace | Best option & very cheap as compared to other options | -- |
| Speaker | -- | Necessary part | Necessary part | -- |
| Capacitors and resistors | -- | Necessary parts | Necessary Parts | -- |
<br />
&nbsp;

These are the things which we could change:
<br />1. Using ESP32 instead of Raspberry Pi as they can perform similar tasks over internet that we want to do. Cost price of Raspberry Pi 3 is 2714 INR whereas cost price of ESP32 is 595 INR which is much cheaper than Raspberry Pi 3. Also, also the functions required in this project can be easily performed by ESP32 like connecting to the internet and downloading the radio files which we want to listen to. It can also be coded to receive the values from the rotary encoder and play the radio station accordingly. It can also drive the audio amplifier which will amplify the audio so that loudspeakers can play the audio.
<br />2. Use of isolation transformer to remove noise that is present. Each audio channel must go through the isolation transformer to clear any noise present before connecting to the amplifier.
&nbsp;

<br />The resources that helped me to find out a better solution are [https://www.instructables.com/id/Internet-Radio-Using-an-ESP32/](https://www.instructables.com/id/Internet-Radio-Using-an-ESP32/) & [https://www.youtube.com/watch?v=F28Znry0qcw](https://www.youtube.com/watch?v=F28Znry0qcw)
&nbsp;

### [2. Connect BLE Weather Sensor to the Cloud](https://www.hackster.io/ble-weather-aws/connect-ble-weather-sensor-to-the-cloud-e79d9d)
#### Ideation:
| Hardware parts used   | Replacable By | Feasibility to replace | Advantages | Disadvantages |
| :---:                 | :---:         | :---:                  | :---:      | :---:         |
| ATmega4809 microcontroller + RN4870/71 module + Raspberry Pi | ESP32 | Very Feasible | Very Cheap | Raspberry Pi can further perform complex process |
| ATmega4809 microcontroller + RN4870/71 module | ESP32 | Very Feasible | Very Cheap | -- |
| ATmega4809 microcontroller | ESP32 | Very Feasible | Very Cheap | -- |
| Weather Click | -- | Necessary to perform action | -- | -- |
<br />
&nbsp;

These are the things which we could change:
<br />1. The combined hardware parts ATmega4809 microcontroller + RN4870/71 module + Raspberry Pi can be simply replaced by ESP32 where it can take data input from weather click and upload it to AWS cloud. This could be on a little disadvantage as Raspberry pi(if we want to) can perform complex process wit the  data collected from the sensor. The main achievement through the replacement with ESP32 board is cost i.e. cost of ESP32 alone is 595INR and for ATmega4809 microcontroller is 1142INR, for Raspberry Pi 3B+ is 2714INR and RN4870/71 module is 431INR and combined price is 4287INR. Also, many steps would be reduced of connecting pi, bluetooth module and microcontroller.
<br />2. The combined hardware parts ATmega4809 microcontroller + RN4870/71 module could also be replaced by ESP32, in this case also price would be reduced by a significant factor.
<br />3. Instead of using ATmega4809 microcontroller ESP32 could also be used, in this case we would surely reduce price.
&nbsp;

<br />The resource that helped me to find out a better solution are [https://hackernoon.com/cloud-home-automation-series-part-1-connect-esp32-to-aws-iot-with-arduino-code-lkhp36vx](https://hackernoon.com/cloud-home-automation-series-part-1-connect-esp32-to-aws-iot-with-arduino-code-lkhp36vx)
&nbsp;
