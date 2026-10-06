# Algoritma

## Perhitungan

### Algoritma Deskriptif

```
  1. Mulai
  2. Masukkan Angka Pertama : 1
  3. Masukkan Angka Kedua : 1
  4. Masukkan Angka Ketiga : 0
  4. Lakukan perhitungan berikut Angka Pertama dikali Angka Kedua Ditambah Angka Ketiga
  5. Tampilkan hasil perhitungan tersebut
  6. Selesai
```

### Algoritma Flowchart

```mermaid
flowchart TD
1@{shape: circle, label: 'Start'}
2@{shape: lean-r, label: 'A: 1; B: 1; C: 0'}
3@{shape: rectangle, label: 'A x B + C'}
4@{shape: lean-r, label: 'Result: 1'}
5@{shape: circle, label: 'End'}
1-->2-->3-->4-->5
```

### Algoritma Pseudo-Code

```pseudo-code
CONSTANT A: 1
CONSTANT B: 1
CONSTANT C: 0
DECLARE Result: INTEGER

Result <- A + B * C

Output "Hasil A + B * C", Result
```
