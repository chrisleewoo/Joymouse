# Joymouse
A mouse replacement using an Arduino Micro (Mega32u4), joystick, and rotary encoder.

Analog joystick:              <br />
              
    GND          
    +5V
    VRx         x-axis        pin A0     
    VRy         y-axis        pin A1      
    SW          left click    pin D11 (input pullup)      
                
-------------------------------------------

Rotary encoder:               <br />

      CLK       right click   pin D4
      DT        scroll up     pin D6
      SW        scroll down   pin D12 (input pullup)
      +
      GND                    


Modified the example sketch named JoystickMouseControl. Be aware that this sketch is only meant to work for the Micro or Leonardo.
  
<iframe src="https://create.arduino.cc/editor/Chrisleewoo/1d5991aa-af45-4a96-8859-bdff87cf46c8/preview?embed" style="height:510px;width:100%;margin:10px 0" frameborder="0"></iframe>
