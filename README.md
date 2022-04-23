* * *
| [Home](https://gand0r.my.id/) | [Catatan](https://gand0r.github.io/catatanku) | [Tentang](https://gand0r.github.io/) |
* * *

### Catatanku

* * *

> Mungkin semua orang bisa copy dan paste, tapi tidak semua orang bisa menganalisa dan solving problem.


* * *

<details><summary>mengganti Dns dengan menggunakan wmic (sudah di coba di windows 7 sp1)</summary>
<p>
   <br>
   - wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ()
   <br>
   - wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ("8.8.8.8", "8.8.4.4")
   
</p>
</details>

* * *

<details><summary>Episode 2</summary>
<p>
   
   mengganti Dns dengan menggunakan wmic (sudah di coba di windows 7 sp1)
   ```
   - wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ()
   - wmic nicconfig where (IPEnabled=TRUE) call SetDNSServerSearchOrder ("8.8.8.8", "8.8.4.4")
   ```
   
</p>
</details>
