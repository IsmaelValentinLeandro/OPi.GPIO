# OPI.GPIO
A modified version of OrangePi.GPIO to bring suport for the Orange Pi Zero2, Orange Pi 3 and the Orange Pi Lite2

###### Installation 

```sudo apt-get update
sudo apt-get install python-dev git
git clone https://github.com/IsmaelValentinLeandro/OPi.GPIO
cd OPI.GPIO
sudo python setup.py install
```

###### Usage
* GPIO.setboard(GPIO.H616) # Orange Pi Zero2 board
* GPIO.setboard(GPIO.PI3) # Orange Pi3 board
* GPIO.setboard(GPIO.LITE2) # Orange Pi Lite2 board

###### To-Do

- [x] Testes de entradas
- [x] Testes de serial


# References
[OPi.GPIO]([https://github.com/rm-hull/OPi.GPIO](https://github.com/rm-hull/OPi.GPIO))

[wiringOP](https://github.com/orangepi-xunlong/wiringOP)

