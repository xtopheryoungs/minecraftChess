### @explicitHints 1

# Chess

## How to Play

Set the names of the players who will play in the ``||mobs:add rule||`` blocks.  See hint for example.

#### ~ tutorialhint
```blocks
let white = mobs.target(ALL_PLAYERS)
white.addRule("name", "Bobby")
let black = mobs.target(ALL_PLAYERS)
black.addRule("name", "Boris")
```

```template
player.onChat("run", function () {
    player.say("Play")
})
let white = mobs.target(ALL_PLAYERS)
white.addRule("name", "myName")
let black = mobs.target(ALL_PLAYERS)
black.addRule("name", "yourName")
```
    
