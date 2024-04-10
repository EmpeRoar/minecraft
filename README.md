# minecraft


```
/give @s command_block
/gamerule commandblockoutput false
```

add 4 command blocks

bottom left 
- repeat 
- unconditional
- always active
```
tp @e[name=camera] ~~3.75~~ facing @p
```

top left
- repeat 
- unconditional
- always active
```
tp @e[name=lens] ~0.1 ~3 ~ facing @p
```

bottom right
- repeat 
- unconditional
- always active
```
effect @e[name=camera] invisibility 1 1 true
```

top right
- repeat 
- unconditional
- always active
```
effect @e[name=lens] invisibility 1 1 true
```