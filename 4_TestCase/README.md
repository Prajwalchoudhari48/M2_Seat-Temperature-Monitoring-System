 # High Level Test Plan
| Test ID | Description | Exp I/P | Exp O/P | Actual Output| Type of Test|
|---| ---| ---| ---| ---| ---|
| H_01 | System Testing | Blink the LED when the passenger is in the seat and the heater is pressed | Pass| Pass| Requirement Based|
| H_02 | System Testing |Convert the analog signal from the temperature sensor to the digital value | Pass| Pass|Boundary Based|
| H_03| System Testing | Generate the PWM signal according to the converted digital value| Pass| Pass| Scenario Based|
| H_04 | System Testing | Send the temperature value to the serial monitor using UART protocol | Pass| Pass|Boundary Based|



# Low Level Test Plan
| Test ID | Description | I/P | O/P | Status|
|---| ---| ---| ---| ---| 
| L_01 |If person seated | Push button1=1  |Push button1=1 | Pass|
| L_02 | If person not seated | Push button1=0	| Push button1=0	| Pass |
| L_03| Temperature Request | Temp=0| Heater=OFF| Pass|
| L_04| Temperature Request | Temp=22| Heater=22 degree generation| Pass|
| L_05| Temperature Request | Temp=28| heater=28 degree generation| Pass|
| L_06| LCD Display | Temperature :22 deg Cel| 20 deg Cel	| Pass|
