# Algoritma

## Algoritma Deskriptif

## Edisi Bilangan Ganjil Genap

```
  1. Mulai
  2. Siapkan sebuah angka
  3. Angka tersebut dibagi 2
  4. Apakah ada sisa dari hasil pembagian tersebut?
  5. Jika tidak, itu genap, jika iya itu ganjil
  6. Selesai
```

## Algoritma Flowchart

```mermaid
flowchart TD
A@{shape: circle, label: 'Start'}
-->
prep[/Siapin Angka/]
-->
if1{Apakah bilangan tersebut mod 2-nya = 0}
if1-->|Yes| R1[/Genap/]
if1-->|No| R2[/Ganjil/]
R1-->stop((Stop))
R2-->stop((Stop))
```
