# BTT_Monoprice_Marlin
I have been trying to flash Marlin and ensure compatibility between my printer monprice maker select v2, main board btt btr v1.4 turbo, and display btt tft35. I attempted using someone's previous Marlin code and changing the stepper and I tried adjusting the code myself. I always get a No Printer connected prompt when I turn on the display. I'm unsure on how to resolve this problem. The common fix was changing the baude rate on the display, that did not work for me.

Marlin 2.0 is the files I used from https://github.com/huseman21/monoprice-bigtreetech/tree/master and alterned to my stepper DRV8825

Marlin 2.1.X.X is the files that I adjusted myself following this guide https://3dwork.io/en/complete-guide-skr-v1-4-and-tmc2209/#Check_the_board_supply_12V_24V

I've toggled the Serial Port and Port 2 in variations [0,-1] and [-1,0], I've adjusted the Baude rates from 250,000 to some of the lower numbers and it does not seem to work
