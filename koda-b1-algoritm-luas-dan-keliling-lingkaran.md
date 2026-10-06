# Minitask Algoritma 3
## Membuat algoritma menghitung luas dan keliling lingkaran

### Deskriptif

```
1. Mulai
2. Masukkan nilai r atau jari-jarinya
4. Hitung luasnya dengan rumus phi dikali 2 kali jari-jari
6. Hitung keliling lingkaran dengan rumus 2 dkali phi dikali jari-jari
8. Tampilkan hasil dari luas dan keliling lingkaran
9. Selesai
```

### Flowchart

``` mermaid
flowchart TD
  1@{ shape: circle, label: "Start" } -->

  2[/Input r/] -->

  3{Hitung luas?}
  3 --> |Ya| 4[Luas = 3,14 * 2 * r]
  3 --> |Tidak| 5[Keliling = 2 * 3,14 * r]

  4 --> 6[/Tampilkan Hasil **Luas**/]
  5 --> 7[/Tampilkan Hasil Keliling/]

  6 --> 8@{ shape: dbl-circ, label: "Stop" }
  7 --> 8@{ shape: dbl-circ, label: "Stop" }
```

## PseudoCode
```
DECLARE phi : DOUBLE
DECLARE r : INTEGER
DECLARE luas : INTEGER
DECLARE keliling : INTEGER
DECLARE is_luas : BOOLEAN

phi <- 3.14

OUTPUT "Masukkan jari-jari :"
INPUT r

OUTPUT "Ingin hitung luas?"
INPUT is_luas

IF is_luas THEN
  luas <- phi * 2 * r
  OUTPUT "Hasil luas lingkaran adalah :", luas
ELSE
  keliling <- 2 * phi * r
  OUTPUT "Hasil keliling lingkaran adalah :", keliling
ENDIF
```
