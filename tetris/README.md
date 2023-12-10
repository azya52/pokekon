# Tetris game for Epoch Game Pocket Computer
Сlone of Game Boy Tetris. Currently only Game A is available.

<img src="https://github.com/azya52/pokekon/blob/main/tetris/img/scr_main.png" width="200"> <img src="https://github.com/azya52/pokekon/blob/main/tetris/img/scr_game.png" width="200"> <img src="https://github.com/azya52/pokekon/blob/main/tetris/img/scr_liftoff.png" width="200">

The game runs on the MAME emulator (though a little slower than it should due to inaccurate emulation) and on the original Pokekon using a custom cartridge with 32kb ROM.

## Build Instructions
Assembly using [Macro Assembler AS V1.42](http://john.ccac.rwth-aachen.de:8000/as/)
```
asl.exe tetris.asm -cpu 78C06
p2bin.exe tetris.p -r $0000-$7FFF
```
