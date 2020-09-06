# TranfficLightSystem-VHDL-

***A VHDL program to simulate Traffic Light System***

**This system includes 9 states: IDLE + S0+S1...S7**

IDLE state is for installing this system.
S0 to S7 is for loop

**7 input：**
      Y means vertical and X means horizontal.
      l and r means left and right.
      The last i means input signal.
      
      1 Left side vertical pedestrian-push button ： key_Y_l_i
      1 Right side vertical pedestrian-push button: key_Y_r_i
      1 Left side horizontal pedestrian-push button: key_X_l_i
      1 Right side horizontal pedestrian-push button: key_X_r_i
      1 50Hz clock input signal: clk_in 
      1 reset input with active 0 :  rst_n   

**12 output**

      Left side horizontal:  1 Red light, 1 Yellow light, 1 Green light.
      Right side horizontal: 1 Red light, 1 Yellow light, 1 Green light.
      Left side vertical:    1 Red light, 1 Yellow light, 1 Green light.
      Right side horicontal: 1 Red light, 1 Yellow light, 1 Green light.


      Left side vertical red-light : Y_red_l_o    
      Y means Versital, l means left and o means output.
