# Undead-C Definition


### Constants
None yet

### Value-Changing Operators
|Name|Example
|:-:|:-:
|Assignment|`a = val`
|Concatenate|`a . b` &nbsp; `a .= b`
|Pre-Increment|`++a`
|Post-Increment|`a++`
|Pre-Decrement|`--a`
|Post-Decrement|`a--`

### Mathematical Operators
|Name|Example
|:--:|:--:
|Addition|`a + b` &nbsp; `a += b`
|Substraction|`a - b` &nbsp; `a -= b`
|Multiplication|`a * b` &nbsp; `a *= b`
|Division|`a / b` &nbsp; `a /= b`
|Modulus|`a % b` &nbsp; `a %= b`

### Bitwise Operators
|Name|Example
|:-:|:-:
|AND|`a & b`
|OR|`a | b`
|XOR|`a ^ b`
|NOT|`~a`
|LSHIFT|`a << b`
|RSHIFT|`a >> b`

### Comparison Operators
|Name|Example
|:-:|:-:
|Equals|`a == b`
|Identical (respects types)|`a === b`
|Not true|`!a`
|Both true|`a && b`
|Any true|`a || b`
|Not equal|`a != b`
|Not identical|`a !== b`
|Less than|`a < b`
|More than|`a > b`
|Less or equal|`a <= b`
|More or equal|`a >= b`
|Is NULL|`??a`

### Keywords
|Name|Usage|
|:--:|:--:|:--:|
|Begin parsing (web-mode)|`<!BEING IN THE DARK IS FUN!>`
|End parsing (web-mode)|`<!POP GOES THE WEASEL!>`
|||
|Start of a procedural program|`QUICK REVIVE`
|End of a procedural program|`DIE MAGGOT`
|||
|stdout|`SCREAM(...)`
|Record stdin <br> return value on `<enter>`|`SPLENDIFEROUS()`
|Define a variable|`BEING name = value`

### Call of Duty Perks
|Name|`DRINK()` ID|Purpose|Usage
|:-:|:-:|:-:|:-:|
|-|-|Loads perk to a custom macro|`BEING name = DRINK(perk)`
|Quick Revive|QUICK_REVIVE|Declare a function|`REVIVE myFunction(...args) {...}` &nbsp; `REVIVE(args) {}`
|Juggernog|JUGGERNOG|Declare a class|`TAKE A TUG OF myClass {...}`
|Mule Kick|MULE_KICK|Declare an array|`EL BURRO(item, item, ...);`
|Double Tap Root Beer|DOUBLE_TAP|Run in a new thread|`YA THIRSTY PARTNER(func);`
|Deadshot Daiquiri|DAIQUIRI|Kill a Thread|`DAIQUIRI WONT FORGIVE(threadID);`
|Speed Cola|SPEED_COLA|While-Loop|`SPEEDCOLA INTENSIFIES {...} UNTIL(condition);`
|Stamin-Up|STAMIN_UP|For-Loop|`SPEEDRUN(array, func)`
|PhD Flopper|PHD|Try-Catch-Finally|`SLAP {...} FLOP(error) {...} REANIMATE {...}`
|Tombstone Soda|TOMBSTONE|Trap SIGINT|`TOMBSTONE {...}`
|Who's Who|WHO|Restart Program after failure|`I FEEL BAD BUT NOT AS BAD AS ME(entrypoint)`
|Electric Cherry|ELECTRIC_CHERRY|Access the process object|`SHOCK();`
|Vulture Aid|VULTURE|Reflect current class as json string|`LOOKING FOR A SIGN();`