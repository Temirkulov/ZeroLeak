# ZeroLeak

ZeroLeak is a Smart Charging System which utilizes a Microcontroller to control the flow of electricity to a mobile phone once the battery percentage reaches around 90% or more. This will be measured using the ACS712 Hall-Effect Current Sensor. This Sensor measures current and sends data to the Arduino Nano MCU in the form of analog data, and the MCU will process this data and calculate the current that passes through the Current Sensor, and then it will estimate the approximate battery percentage of the mobile phone using the current data. 

Once the mobile phone reaches 90%, the relay will be powered to open the circuit and stop the flow of current into the mobile phone, thus helping to extend the battery lifetime of the mobile phone. 



