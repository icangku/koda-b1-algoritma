# Algoritma

## Looping

### Flowchart

```mermaid
flowchart TD

1@{shape: circle, label: 'Start'}
2@{shape: lean-r, label: 'Init i=0'}
3@{shape: diamond, label: 'i <= 5?'}
4@{shape: lean-r, label: 'Output i'}
5@{shape: rectangle, label: 'i++'}
6@{shape: circle, label: 'Finish'}

1 --> 2 --> 3 --> 4 --> 5 --> 3
3 --> 6
```

## FizzBuzz - Setiap Angka Genap jadi FizzBuzz

### Pseudocode

```pseudocode
DECLARE Number: Integer
Number <- 0

REPEAT
  Number <- Number + 1
  IF Number MOD 2 = 0 THEN
    OUTPUT "FizzBuzz"
  ELSE
    OUTPUT Number
  ENDIF
UNTIL Number > 10
```

```mermaid
flowchart TD

A@{shape: circle, label: 'Start'}
B@{shape: lean-r, label: 'i = 0'}
C@{shape: diamond, label: 'i <= 10 ?'}
D@{shape: rectangle, label: 'i++'}
E@{shape: diamond, label: 'i % 2 == 0 ?'}
F@{shape: lean-r, label: 'FizzBuzz'}
G@{shape: lean-r, label: 'i'}
H@{shape: dbl-circ, label: 'Finish'}

A --> B --> D --> E -->|Yes| F --> C
E --> |No| G --> C --> D
C --> H
```
