
# Favori Linux Shell Komutlarım
Linux'u kullanırken işime yarayan ve sevdiğim shell komutlarını burada saklıyorum.

`du . -sh`<br>
Mevcut dizinin diskte ne kadar yer kapladığını gösterir.

`du . -Sh -d 1`<br>
Mevcut dizin ve birinci seviyedeki (-d 1) alt dizinlerin diskte ne kadar yer kapladığını gösterir.

`uname -a`<br>
Linux'a ait tüm sistem bilgisini gösterir. Sadece Linux çekirdek sürümü gerekiyosa `-r` parametresi kullanılabilir.

`netstat -antup`<br>
Tüm ağ bağlantılarını listelemek için kullanılır. 
- a: Tüm bağlantılar (sadece dinleyen soketleri görmek için -l kullanılır.)
- n: Sayısal adresleri göster
- t: TCP bağlantılarını göster
- u: UDP bağlantılarını göster
- p: Program bilgisini göster
