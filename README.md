### Catatanku
* * *
> Mungkin semua orang bisa copy dan paste, tapi tidak semua orang bisa menganalisa dan solving problem.

* * *
Cara mengganti Dns dengan menggunakan prompt

1. Hapus DNS
> wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ()
2. Menambah DNS
> wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ("8.8.8.8", "8.8.4.4")

