## Maze Game

This came out of discussions between Kevin Buzzard and Kendall Frey on the Xena Discord.

## The game.

You're in a maze of twisty passages, all alike! You can go North, South, East or West. Look for the exit!

Brought to you by the Xena Project.

## How to play

To install locally, you need to make you have the leanprover community mathlib tools installed.
See [here](https://leanprover-community.github.io/get_started.html#regular-install) for instructions for how to install on your OS.

Then do

```
leanproject get kbuzzard/maze-game
```

and open the project with the "open folder" functionality of VS Code, or by using
```
cd maze-game
code .
```

on the command line.


## Can we play on CoCalc?

Great question! Here's hoping.

## Playing the example maze

You need to open the file `level.lean` in `src/example_maze`, in a Lean editor like VS Code.



The map of example maze is defined to be:

```text
01
23
 4
```

The start is defined to be 0, and
the end is defined to be 4.

## Interesting questions

Can people write python code which designs levels?

Can people write Lean code which solves levels?

How far can each system go?



