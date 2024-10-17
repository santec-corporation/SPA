## Error Codes

### Settings Error Codes

#### `SetOperationSettings()` or `LoadOperationSettingsINI()`

Get a list of encountered error codes using GetSettingsErrors.

-10 = StartWave not in limits <br>
-11 = StopWave not in limits <br>
-12 = StartWave >= StopWave <br>
-13 = StartWave or StopWave in water absorption region <br>
-14 = Measurement Mode not valid (valid 0 - 3) <br>
-15 = Refractive Index not valid (valid > 1) <br>
-16 = Power not valid (valid -3 to 10) <br>
-17 = StartWave or StopWave <= 0

### Connection Error Codes

#### `LoadConnectionSettingsFromFile()`
-1 = File does not exist <br>
-2 = Invalid file format <br>
-3 = Unable to parse file <br>
-4 = Invalid TSL Type <br>
-5 = Invalid GPIB Address <br>
-6 = Invalid USB Device ID

### Instrument Error Codes

#### `SetScanSettings()` and `StartScan()`
-1 = Unable to read information from device <br>
-10 = Unable to read information from device <br>
-14 = Unable to read information from device <br>
-40 = Unable to start measurement (check TSL is not dark) <br>
-200 = TSL is currently not in a sweepable state <br>
-222 = Out of settable range <br>
int.MinValue = Unexpected exception

#### `GetSamplingData()`
-1 = If Sample count = 0 <br>
-2 = High-frequency triggering error
