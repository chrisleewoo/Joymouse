# Joymouse
A mouse replacement using an Arduino Micro (Mega32u4), joystick, and rotary encoder.

Analog joystick:              <br />
              
    GND          
    +5V
    VRx         x-axis        pin A0     
    VRy         y-axis        pin A1      
    SW          left click    pin D3      
                
-------------------------------------------

Rotary encoder:               <br />

      CLK       right click   pin D4
      DT        scroll up     pin D6
      SW        scroll down   pin D7
      +
      GND                    


Modified the example sketch named JoystickMouseControl. Be aware that this sketch is only meant to work for the Micro or Leonardo.
  
