# Treason: Checkers for the Paranoid

This is an implementation of a variant of checkers called Treason.

It is written in Ruby on Rails.

## Rules:
The rules are the same as the checkers, with the following additions:
* At the beginning, both players select two pieces from the opponents side. These are their Operatives.
* Neither player knows which of their pieces are their opponents Operatives.
* At any point during a players turn, they may select one of their Operatives to become their piece. This does not use the players turn.
* Until the Operative is turned, it is treated as a normal piece.
