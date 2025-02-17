# Robot
This is a robot I made to deliver things around my room, and I was going to make it use a distance sensor, but that did not work out,a nd I did not have enough time for a claw.
## BOM
To make one for youself you would need an Arduino Uno, Any motor driver, 6 Batteries, MPU 6050, a 3/4 caster wheel, 2 encoder motor, 1 button, 2 sheels, and some jumper wires.
## How to make it
You can screw most of the parts together, but the main challenge is the wireing. This can be adjusted in code, but 
my robot has 
R1 = 12         
R2 = 6
L1 = 8
L2 = 5
pwm for the Left motor = 10
pwm for the right motor = 11
Right encoder pin = 2
Left encoder pin = 3
Button is connected between 4 and 5V
The Gyroscope is connected to SDA and SCL
The GND< and %V are all connected to the one on my motor driver. 
The Battery's 9V is supplied to my motor driver.
## Nect steps
In the future I am going to work on a claw and adding back a distance sensor, so please check in again later. 
