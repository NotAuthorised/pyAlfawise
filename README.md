PyAlfawise
===================

![AlfaWise Humidificateur](http://sarakha63-domotique.fr/wp-content/uploads/2018/02/diffuseur.jpg)

### <i class="icon-book"></i> Library

**PyAlfawise** :bulb: is a simple python3 library for the Alfawise Humidifier.

  - This library is under development but still usable
  - This library has been developed above the work of [sarakha63](https://github.com/jeedom/plugin-alfawiseumist)
  - The tests are only made with my own model which is the one on the picture above. If you have any other model that can match with this library please feel free to PR.
  - There is no official API for now, so this library can be broken at any time.

### <i class="icon-check"></i>TODO

- [ ] Add test coverage
- [ ] Add the library to Pypi
- [ ] Correct some bugs (see TODO in code)
- [ ] Add possibility to ask the device back for its current state (reverse engineering needed)
- [ ] .... and lots of things !
 
### <i class="icon-cog"></i> How-To

1. You have to setup your device with the AMA app to connect it to your local wifi network.
3. Determine your bulb ip and mac address (using router, software, ping and so on)
4. Open your favorite python3 console  
```
>>> import pyAlfawise
>>> device = pyAlfawise.Alfawise("mac address without :", "ip address")
>>> device.turn_on(255,0,0)
```

### <i class="icon-plus"></i>What can I add ?

  - PR are welcome
  - Advices on library structure are welcome too, this is one of my first python library and I'm still a noob on Python code
  - If you want to contact me : <i class="icon-twitter"></i> @hydreliox on Twitter