# ArduGame
## About
I first came across the Arduboy when I watched Short Circuit's [video](https://www.youtube.com/watch?v=R6doWcA6q6Y) about the Arduboy Mini, and I was in awe of the super cool device it is. As a fun weekend project, I put together an Arduboy on a protoboard, and after playing on the very janky-looking protoboard for a while, I decided to make a PCB for it which I call the ArduGame.

![image](https://github.com/abhignay/ArduGame/assets/74813604/0791ee10-4cda-426d-8bd0-e704fe2cc03c)


## Hardware
The ArduGame uses an Arduino Pro Micro as its microcontroller, and an SH1106 1.3" SPI OLED as its screen. Additionally, there's a TP4056 LiPo manager along with a 3.3V to 5V step-up converter (MT3608). I've designed the ArduGame to be powered by a 3.3V LiPo battery

## Software
To be able to upload game files (in the .ino file format) download MrBlinky's [Arduboy-homemade-package](https://github.com/MrBlinky/Arduboy-homemade-package) and upload your favorite game!

If you have any questions, comments or suggestions open up an issue!

## License

Code in this repository is licensed under the terms of the MIT license.
