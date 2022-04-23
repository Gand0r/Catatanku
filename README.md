### Catatanku
* * *
> Mungkin semua orang bisa copy dan paste, tapi tidak semua orang bisa menganalisa dan solving problem.

* * *
Cara mengganti Dns dengan menggunakan prompt
>#!/bin/bash
# Program name: pingall.sh
date
cat /home/edp/myip.txt |  while read output
do
    ping -c 1 "$output" > /dev/null
    if [ $? -eq 0 ]; then
    echo "koneksi $output is up" 
    else
    echo "koneksi $output is down"
    fi
done
