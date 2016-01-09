# frame-data
Fighting game character frame data in json and csv formats.

# [Ultra Street Fighter 4]
## Attack Legend
Notation|Expanded
--------|--------
lp|Light Punch / Jab
mp|Medium Punch / Strong
hp|Hard Punch / Fierce
lk|Light Kick / Short
mk|Medium Kick / Forward
hk|Hard Kick / Roundhouse

## Character State Legend
Notation|Expanded
--------|-------
s|Standing
cs|Close Standing
cr|Crouching
nj|Neutral Jump / Jump Up
dj|Diagonal Jump / Jump Toward

## Frame Data Legend
Notation|Expanded
--------|--------
s|Startup
a|Active
r|Recovery
ba|Block Advantage
ha|Hit Advantage

## JSON Schema
```
{
  normal-attack: {
    standing: { startup: num, active: num, recovery: num, block-advantage: num, hit-advantage: num }
    close standing: {...}
    crouching: {...}
    neutral jump: {...}
    diagonal jump: {...}
  }
  unique-attack: {...}
}
```
