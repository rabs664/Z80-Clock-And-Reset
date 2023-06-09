# Z80-Clock-And-Reset
Simple 555 based astable and monostable clock and reset board.

![Z80-Clock-And-Reset-Image](https://github.com/rabs664/Z80-Clock-And-Reset/assets/105534000/29275150-0e0f-4498-9a1d-9f33c6b0b92a)

The Z80 Clock and Reset board provides a variable astable clock where the frequency can be controlled by R8 or a monostable clock to allow the clock to be "single-stepped". The switch S1 toggles between the astable and monostable clock. Additional the switch S3 provides a reset signal for use with the Z80. Note on V1.1 of the board the active low and high reset lables are in fact the wrong way round! 

Astable Clock Output

![Z80-Astable-Clock-Image](https://github.com/rabs664/Z80-Clock-And-Reset/assets/105534000/8fe6f946-6bfd-4748-a389-0d7d6ed96b9a)

## Objective
Support Z80 CPU learning, specifically used with associated [Z80 CPU](https://github.com/rabs664/Z80-CPU), [Z80 Memory](https://github.com/rabs664/Z80-Memory) and [Z80 Bus Monitor](https://github.com/rabs664/Z80-Bus-Monitor) Boards.

## Background
Used extensively during early Z80 learning to single step the clock or slow run the clock and watch the Z80 activity using the [Z80 Bus Monitor](https://github.com/rabs664/Z80-Bus-Monitor) Board.

## Testing
The Z80 Clock and Reset V1.1 board has been built and tested. 

Note there is a V1.2 in development to resolve a couple of minor issues. 

## Acknowldgements
Ideas and Information.

Thanks to Don Prefontaine and Peter Murray, and their excellent [Zed80 Website](http://zed80.com/Z80-RETRO/index_Home.html) from which the basis of this board has been taken.

# Release History
## Version 1.1
* First Release
