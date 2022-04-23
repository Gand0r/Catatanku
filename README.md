### Catatanku
* * *
> Mungkin semua orang bisa copy dan paste, tapi tidak semua orang bisa menganalisa dan solving problem.

* * *
Step mengganti Dns dengan menggunakan wmic (sudah di coba di windows 7 sp1)

- Hapus DNS
> wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ()
- Menambah DNS
> wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ("8.8.8.8", "8.8.4.4")

<details><summary>1</summary>
<p>
#### Step mengganti Dns dengan menggunakan wmic (sudah di coba di windows 7 sp1)
    ```wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ()
    wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ("8.8.8.8", "8.8.4.4")```
</p>
</details>
