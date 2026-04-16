# Godot: Pins

> Abstract tool to simulate an electronic pin in Godot, ignoring the rest of the complexity.

Add to a git project:
```
git submodule add https://github.com/EloiStree/2026_04_11_gdp_pins.git addons/2026_04_11_gdp_pins
```

Add to a non-git project:
```
git clone https://github.com/EloiStree/2026_04_11_gdp_pins.git addons/2026_04_11_gdp_pins
```


### To Do

- Black, Ground Pin: 
 -  With estimated volt out
- Red, Volt in Pin:
 - With volt in
 - Min Volt to work
 - Max volt to stop
 - Volt to break
- Signal, Volt out pin:
	- Percent Value out
	
	
Hard to implement for later:
- Read / Write Pin, Micro Controller:
- Under frame UART and PWM feature.




------------

💡 Une bonne idee que j ai eu en parlant avec Vincent. Avoir des pins udp et pin websocket. En gros des pins configurables avec un peu de byte control. Donc le but de permettre du "creative mode." externe.
