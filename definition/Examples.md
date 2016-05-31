# Hello World Programs

## Smallest program
```
QUICK REVIVE {
    SCREAM("Hello World");
}
```

## OOP Program
```
TAKE A TUG OF helloClass {
    REVIVE sayHello(name) {
        SCREAM("Hello " . name);
    }
}

BEING instance = SPAWN(helloClass);
BEING name = SPLENDIFEROUS();
instance->sayHello(name);
```

## Web-Mode
```
<html>
<body>
    <h1>
        <!BEING IN THE DARK IS FUN!>
            SCREAM("Hello World!");
        <!POP GOES THE WEASEL!>
    </h1>
</body>
</html>
```

## Redefine perks
```
# Import QuickRevive and assign it to the var 'func'
BEING func = DRINK(QUICK_REVIVE);

# Use the alias
func hello(name) {
    SCREAM("Hello" . name);
}

hello(SPLENDIFEROUS());
```
