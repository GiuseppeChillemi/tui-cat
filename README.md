# Tui-cat

RED language TUI engine based PAC-MAN like game

Download the TUI Branch, compile the console as `-t MSDOS` and run it

https://github.com/red/red/tree/TUI


The console file in `environment/console/CLI/console.red` needs this modification in the header:

```
	Needs:	[JSON CSV VIEW]
	Config: [GUI-engine: 'terminal]
```

Compile it with...

`do/args %red.r "-r -t MSDOS %environment/console/CLI/console.red"`

...and run the game with `console.exe tui-pac.red`

The game is a SPEEDRUN Pacman with no ghosts, they will be added later 

Have fun!

Giuseppe Chillemi

