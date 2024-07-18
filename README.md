# e-bike torque to throttle, test


Discussion en français sur le [forum Cyclurba](https://cyclurba.fr/forum/751958/arduino-l-assistance-d-un-vae.html?from=221&discussionID=31032&messageID=751958)  


### Torque sensor   
marque AXLETORQUEBB68MM (Aliexpress)
5V 50mA MAX, 35mA standard, sortie 0.8-3.7v, 44mV/Nm, 75 Nm max  
<p align="left">
  <img src="./docs/torque_sensor.jpg" width="400" title="reed diagram">
</p>

### sensor pin out  
<p align="left">
  <img src="./docs/tork_connector.jpg" width="400" title="reed diagram">
</p>

### Diagram Arduino Nano
<p align="left">
  <img src="./docs/diagram_tork_throttle.jpg" width="700" title="digispark led">
</p>

### Torque diagram
[Source, voir son pdf](https://www.mdpi.com/1424-8220/23/10/4657 " voir son pdf")  
<p align="left">
  <img src="./docs/tork_diagram.jpg" width="700" title="digispark led">  
</p>

  
### Mon générateur de signal ebike  
<p align="left">
  <img src="./docs/banc_test1.jpg" width="700" title="digispark led">
</p>

### signal PWM OUT
filtre RC comme sur schéma, vérification sur oscillo + voltmètre de labo  
<p align="left">
  <img src="./docs/banc_test2.jpg" width="700" title="digispark led">
</p>
