# Minitask PseudoCode

### Deskriptif

```
1. Mulai
2. Masukkan angka 1 pada variabel A
3. Masukkan angka 1 pada variabel B
4. Masukkan angka 0 pada variabel C
5. Hitung angka A dikali B ditambah C
6. Tampilkan hasilnya
7. Selesai
```

### Flowchart
``` mermaid
flowchart TD
  start((start))
  A[/A = 1/]
  B[/B = 1/]
  C[/C = 0/]
  hasil[Hasil = A * B + C]
  print[/Tampilkan hasil/]
  final(((end)))
  start --> A --> B --> C --> hasil --> print --> final
```

### Pseudo Code
``` pseudocode
DECLARE A : INTEGER
DECLARE B : INTEGER
DECLARE C : INTEGER
DECLARE HASIL : INTEGER

A <- 1
B <- 1
C <- 0
HASIL <- A * B + C

OUTPUT "Hasil dari A * B + C adalah : ", HASIL
```

### Pseudo Code Function
``` pseudocode
FUNCTION Aritmatika(a : INTEGER, b : INTEGER, c : INTEGER) RETURNS INTEGER
  RETURN a * b + c
ENDFUNCTION

OUTPUT "Hasilnya adalah :", Aritmatika(1, 1, 0)
```
