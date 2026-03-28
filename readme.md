# myLEDsnake

## 1D Game for myRIO (or other NI RIO targets)

This game can be used with a myRIO to read 3 buttons, and output data to a WS2812 addressable LED strip. On the strip there is a snake with different colors moving towards the player. The player can press one of three buttons (red, yellow, blue) to "shoot" that color. It will fly towards the snake. If the snake is hit with the correct color, it will disappear. If a false color is shot, it will append to the end of the snake.

## LabVIEW Rework

This is a LabVIEW rebuild of an older project of mine implemented on an esp32:
https://www.youtube.com/watch?v=YRH0OxSvn9c
