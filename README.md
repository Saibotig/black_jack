# black_jack
A console game in c++ where you can play black jack against the computer


## Architecture

#### Components

The game is written in a component orientaded architecture.

Visual there is the console component.
Then we have the game_logic component, which interacts with the player and ai component.

#### Modules

The console component can be devided in several modules:

- Player Input
- Game Table


The game_logic component:

- End Turn Who won?
- Statemachine turns
- Start of Game. How much players?
- Data Structure of Game. Cards
- Runout protection of cards. Schuffle Cards

The player component

- game functions, raise, trow, one more card, hold

Expension pack:
- new game, save game
- add, delete ai player


The ai component

- first choose random logic

Expension pack:
- analyses cards
- statistic outcome of game
- deepsearch and heuristik
