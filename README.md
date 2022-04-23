### Catatanku
* * *
> Mungkin semua orang bisa copy dan paste, tapi tidak semua orang bisa menganalisa dan solving problem.

* * *
Step mengganti Dns dengan menggunakan prompt

- Hapus DNS
> wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ()
- Menambah DNS
> wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ("8.8.8.8", "8.8.4.4")

