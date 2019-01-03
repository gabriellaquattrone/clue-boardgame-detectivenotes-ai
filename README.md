# Clue

## Authors

Gabriella Q and Jenny S

## How to play

### Objective

Determine who killed the victim, with what weapon, and where.

### Commands

To start the game, run `swipl clue.pl`.

You will be prompted for the number of players, the players in the order of term, which player you are, and your starting hand. From  here on out, all your responses must end with a `.`!

From there you can use `suggest(SUSPECT, WEAPON, ROOM).` to try and gather information about what cards are in the "Case File" envelope.

You can record other player's responses using `record(PLAYER, SUSPECT, WEAPON, ROOM).`.

When you need to reference your clue sheet to see what information you've gathered about the game by calling `cluesheet.`

If you need help making a suggestion, write `help.`
We'll come up with a suggestion for you to use.

## Clue Items

Equipment: 9 rooms, 6 players, 6 Weapons

Rooms: kitchen, ballroom, conservatory, diningroom,
           billiardroom, library, lounge, hall, study

Players: colonelmustard, missscarlet, professorplum,
             mrgreen, mswhite, mrspeacock

Weapons: rope, leadpipe, knife, wrench, candlestick, pistol

Cards: One Card for Each of the 6 Suspects, 6 Weapons, and 9 Rooms
       This means there will be 21 Cards in total. Something to keep in mind.

Confidential "Case File" Envelope: the secret solution. Of the 21 cards in play, 3 of them are in the envelope. Figure out which ones are in there to beat the game!

## Clues about CLUE

The cards in your own hand can't include anyone, anything, or any location that was involved in the crime! Those should be ruled out immediately.

We know that the envelope only consists of one of each of the following: suspect, weapon, and crime scene. There should be no duplicates.


## Deliverables

* initialize the game set up easily
    * [X] which rooms and weapons are used in this version of the game?
    * [X] how many Players
    * [X] the order of play (who's turn is next?)
    * [X] which cards am I holding?

* keep track of user own play
    * [X] I tell the program my suggestion
    * [X] I tell the program what I learned

* the program should allow me too:
    * [X] see the contents of the database on demand
    * [X] know when to make the accusation

* extras
    * [X] electric note pad
    * [X] record suggestions
    * [X] give suggestions to player
    * [-] build models of what the other players might know
    * [X] advise suggestions to throw other players off