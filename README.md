# eshome_sump_pump_control
ESP Home Sump Pump Control

The default watchdog sump pump control system seems to kill deep cycle batteries.  
It's time to rip the whole thing out, make it compatible with home assistant and comibe it with the asump pump water level monitor to a complete sump  https://ezmation.com/content/7-sump-pump-water-level

This simple system:
- Monitors the float sensor and enables the pump when the water level gets too high
- Uses a backup ultrasonic sensor to check the sump pump water level
- handles the cases where the float sensor turns off too quick or doesn't turn off at all
- monitors the sump pump battery
- integrates with home assistant.
- 
