1. Przygotowanie konfiguracji sieci zgodnie z poniższym diagramem

![diagram1](/ćwiczenia-3/cwiczenia3.svg)

2. Przetestowanie połączenia poleceniem ping

Na systemie PC1 wpisuję ``ping 172.16.100.11`` oraz sprawdzam poprawność połączenia

![ping](/ćwiczenia-3/ping.png)

3. Testowanie komunikacji między PC1 a PC2 korzystając z programu ``HTTP CHAT``

Na PC2 instaluję program ``HTTP CHAT`` oraz uruchamiam httpchat za pomocą polecenia ``python httpchat.py``

Na PC1 za pomocą polecenia ``curl -X POST -d '{"text": "Hello World"}' http://172.16.100.11:8888/chat`` oraz sprawdzam czy na PC2 wiadomość się wyświetliła.

![httpchat](/ćwiczenia-3/httpchat.png)

4. Konfiguracja PC3 pod kontrolą systemu Windows według poniższego diagramu

![diagram2](/ćwiczenia-3/cwiczenia3.1.svg)

5. Weryfikacja połączenia korzystając z przeglądarki, odwiedzając graficzny interfejs ``HTTP CHAT`` pod adresem ``http://172.16.100.10:8888``
