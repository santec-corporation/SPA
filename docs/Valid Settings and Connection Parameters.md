## Valid values for Settings INI

**LimitMinWave <= StartWave <= LimitMaxWave**
- Floor StartWave to LimitMinWave

**LimitMinWave <= StopWave <= LimitMaxWave**
- Ceiling StopWave to LimitMaxWave

**StartWave >= StopWave**
- If not valid, set StartWave and StopWave to LimitMinWave and LimitMaxWave resp.

**1350 <= StartWave <= 1420, 1350 <= StopWave <= 1420**
- Water Absorption Wavelengths
- If not valid, set to LimitMinWave and LimitMaxWave

**MeasurementMode: 0, 1, 2, 3** <br>
0 = Port 1, 1 = Port 2, 3 = Port 3, 4 = IL (Transmission)

**DefaultRefractiveIndexValue >= 1**
- If not valid, set to 1

**AverageCount >= 1**
- If not valid, set to 1

**-3 <= Power <= 10**
- If not valid, set to -3

**Gain: 0, 1, 2, 3, 4** <br>
0 = auto, 1 = 0 dB, 2 = 4 dB, 3 = 9 dB, 4 = 13 dB

 <br>

## Valid values for Connection INI

**TSL Communication: USB, GPIB, LAN**

If _TSL Communication = GPIB_, <br>
   GPIBAddress = 0 - 30 <br>  <br>
If _TSL Communication = USB_, <br>
   USBDeviceID > 0 <br>  <br>
If _TSL Communication = LAN_, <br>
   IP and Port must be valid <br>

SPA Device ID must be of form "Dev#", where # is > 1.

   w2500fm, <br>
   w5pm, <br>
   w10pm, <br>
   w20pm, <br>
   w40pm, <br>
   w80pm, <br>
   w160pm, <br>
   w320pm, <br>
   w640pm, <br>
   w1281pm, <br>
   w2564pm
