# OpenGestureControl for Micro:bit
Control your OpenGestureControl instance using a Micro:bit.

## How to install
- Make sure yotta is correctly installed
- Run `yotta target bbc-microbit-classic-gcc`
- Run `yotta build`
- Flash build/bbc-microbit-classic-gcc/source/OpenGestureControl-combined.hex onto the Micro:bit

If you run into issues during the build step, please look at yotta's debug output to find out what extra packages you may be missing.

## How to use
Turn the micro:bit on and wait for the text "RDY" to scroll by. Then, connect to it through the OpenGestureControl Desktop application. The micro:bit will display "I" while idle, "C" while connected and "D" after disconnecting.

## License
MIT
