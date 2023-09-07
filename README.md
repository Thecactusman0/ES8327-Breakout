# ES8327 Breakout
 Breakout/testing board for the ES8327 dual channel audio CODEC

 Wouldnt recommend building, works but could be done better.
 Mclk should be on either 0,1 or 3. Not 32. There should also be a 10k pulldown on the left out channel. This resistor is not in the datasheet but is required for the interrupt. On the  topic of the interrupt it needs to be moved from io2 as depending on how its configured you can stop the esp32 booting. Among other small things.
 Working on a standalone breakout for this chip, stay tuned.
