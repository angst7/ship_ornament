# ship_ornament
Starship Christmas tree ornament (KiCad)

This is a quick christmas tree ornament that I built with my daughter.  It features LEDs on each nacelle, an LED over the bridge area, and an LED on the reflector.

The LEDs are routed to four PWM output pins of an 14 pin TSSOT STM32L011 to allow flexibility in the light output level and the ability to do some lighting tricks.  If a microcontroller isn't desired, current limiting resistors can be populated for each LED, and the battery can be soldered directly to the resistors.

The battery is a CR2032.  The footprint is for part BAT-HLD-001 available at digikey and mouser. 

All the passives and LEDs are 0603.
