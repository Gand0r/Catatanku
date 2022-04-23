* * *
[Back to home](https://gand0r.my.id/) | [Tentangku](https://gand0r.github.io/)
* * *

### Catatanku

* * *

> Mungkin semua orang bisa copy dan paste, tapi tidak semua orang bisa menganalisa dan solving problem.


* * *

<details><summary>0000</summary>
<p>
   mengganti Dns dengan menggunakan wmic (sudah di coba di windows 7 sp1)
    
   - wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ()
   - wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ("8.8.8.8", "8.8.4.4")
   
</p>
</details>
