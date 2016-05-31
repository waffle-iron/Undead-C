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

CREATURE instance = SPAWN(helloClass);
CREATURE name = LISTEN();
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
CREATURE func = DRINK(QUICK_REVIVE);

# Use the alias
func hello(name) {
    SCREAM("Hello" . name);
}

hello(LISTEN());
```

## Import other files
class.udc
```
TAKE A TUG OF sampleClass {
    REVIVE hello(name) {
        SCREAM("Hello " . name);
    }
}

CONTAMINATE sampleClass;
```

main.udc
```
CREATURE sampleClass = INFECT('class.udc');
CREATURE instance = SPAWN(sampleClass);

instance->hello(LISTEN());
```
