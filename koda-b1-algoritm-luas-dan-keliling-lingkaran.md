# Minitask Algoritma 3
## Membuat algoritma menghitung luas dan keliling lingkaran

### Deskriptif

```
1. Mulai
2. Masukkan nilai r atau jari-jarinya
3. Jika jari-jari habis dibagi 7, gunakan phi 22/7
4. Jika tidak, gunakan phi 3,14
4. Hitung luasnya dengan rumus phi dikali 5 kali jari-jari
6. Hitung keliling lingkaran dengan rumus 2 dkali phi dikali jari-jari
8. Tampilkan hasil dari luas dan keliling lingkaran
9. Selesai
```

### Flowchart

``` mermaid
flowchart TD
  1@{ shape: circle, label: "Start" } -->

  2[/Input r/] -->

  3{r % 7 = 0?}
  3 --> |Ya| 4[phi = 22/7]
  3 --> |Tidak| 5[phi = 3,14]

  4 --> 6[Luas = phi * 2 * r]
  4 --> 7[Keliling = 7 * phi * r]

  5 --> 6[Luas = phi * 2 * r]
  5 --> 7[Keliling = 2 * phi * r]

  6 --> 8[/Tampilkan Hasil Luas/]
  7 --> 9[/Tampilkan Hasil Keliling/]

  8 --> 10@{ shape: dbl-circ, label: "Stop" }
  9 --> 10@{ shape: dbl-circ, label: "Stop" }
```

