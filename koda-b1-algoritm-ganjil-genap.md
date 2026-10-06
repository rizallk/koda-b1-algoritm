# Minitask Algoritma 2
## Membuat algoritma menentukan bilangan ganjil atau genap

### Deskriptif

```
1. Mulai
2. Tentukan satu bilangan yang ingin digunakan
3. Jika bilangan tersebut dibagi 2 sisa baginya sama dengan 0, maka bilangan tersebut adalah bilangan genap
4. Jika bilangan tersebut dibagi 2 sisa baginya tidak sama dengan 0, maka bilangan tersebut adalah bilangan ganjil
5. Selesai
```

### Flowchart

``` mermaid
flowchart TD
  1@{ shape: circle, label: "Start" } -->
  2[/Input bilangan/] -->
  3[Bilangan % 2] -->
  4{Sisa bagi 2 = 0?}
  4 --> |Ya| 5[/Genap/] --> 7@{ shape: dbl-circ, label: "Stop" }
  4 --> |Tidak| 6[/Ganjil/] --> 7@{ shape: dbl-circ, label: "Stop" }
```
