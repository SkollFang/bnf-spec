PAL-J
=====

A small Domain Specific Language designed for entry level programming of simple graphical games.

PAL-J programs consist of three files, one for asset loading and initialization of persistent variables (game.init), one describing rendering functions (game.render, with access to the program canvas) and lastly, a control file (game.tick) containing the entry point and `scene`'s that listen for input and take action.

See ./Reference.md for a high level overview of keywords and contexts, and ./PAL-J.bnf for a formal language specification.

Examples
--------
- Asteroids (./asteroids)
- Fighter (./fighter)

