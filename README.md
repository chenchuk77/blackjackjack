# BlackJackJack
### BlackJack game written in Jack language

Blackjack game implementation for the hack platform, written in 
[Jack](https://drive.google.com/file/d/1rbHGZV8AK4UalmdJyivgt0fpPiD1Q6Vk/view) language.

### Compile the game
the game shipped with a compiler in the tools directory.
compile the BlackJack directory:
```
$ ./tools/JackCompiler.sh BlackJack
```
The compiler will output the compiled vm code files inside 
that folder.
***

### Running the game
A virtual machine emulator will be used to run the compiled vm code.

```
$ ./tools/VMEmulator.sh
```
after launching the VMEmulator:
*  Load the BlackJack directory
*  Set Animato to: 'no animation'
*  Press RUN ( >> )

***
### NOTES
* VMEmulator and JackCompiler are not written by me, it shipped so it can be built and run.
* Random.jack was not written by me

***
### TODO:

