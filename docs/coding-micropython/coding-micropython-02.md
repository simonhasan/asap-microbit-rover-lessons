# Moving the Rover Forward and Reverse

## Import the Libraries
TODO
```python
from microbit import *
from motorbit import Motorbit
```

## Instanciating a `Motorbit` Object
TODO
```python
rover = Motorbit()
```

## Moving the Rover Forward
TODO
```python
rover.set_motor_speed(100, 100)
```

## Stopping the Rover
TODO
```
rover.set_motor_speed(100, 100)
sleep(1000)
rover.set_motor_speed(0, 0)
```

## Moving the Rover in Reverse
TODO
```python
rover.set_motor_speed(-100, -100)
sleep(1000)
rover.set_motor_speed(0, 0)
```

## Moving the Rover Forward and in Reverse in a Loop
TODO
```python
# Imports go at the top
from microbit import *        # Import all the microbit library functions
from motorbit import Motorbit # Import Motorbit from the motorbit library

# Instantiate the Motorbit object
rover = Motorbit() # rover is an instance of the Motorbit class

# Code in a 'while True:' loop repeats forever
while True:
    rover.set_motors_speed(100, 100)   # Set the speed of both motors to 100
    sleep(1000)                        # Wait for 1 second
    rover.set_motors_speed(-100, -100) # Set the speed of both motors to -100 
    sleep(1000)                        # Wait for 1 second
```
$\frac{1}{\sqrt{2}}$