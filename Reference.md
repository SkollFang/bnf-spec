Keywords and contexts
=====================

game.init
---------
- `create <name>`
- `as <name>`
- `set <array>`
- `to <index> <array>`
- `loadSprite <file> as <name>`
- `loadGif <file> as <name>`
- `loadSound <file> as <name>`
- `loadVideo <file> as <name>`
- `loadBackground <file> as <name>'

game.render
-----------
- `collapse(args..): `
- `collapseGif(args..):`
- `collapseFlip(args..):`
- `sync(arg, t1, arg1, t2,...):`
- `output(args..):`
- `event <name> [<arg1>, ...] <body> end event`
- `action <name> [<arg1>, ...] <body> end event`
- `block <name> [<arg1>, ...] <body> end event`

game.tick
---------
- `scene <name> <body of Events/Block/Actions> end scene`
- listen <input method> <event/action/block> \n
- run := key word used to activate action/event
- and := key word used to join more than one input simultiously
- delay := key word used when input is alternate to previous input
- during := key word used with input type of an already recent event/action/block
- <block name>.<action/event> \n
- setValue <name> <value> \n
- setBackground <name> \n
- setFloorlevel <pixel height from bottom> \n