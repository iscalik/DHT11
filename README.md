DHT 11 Sıcaklık ve Nem Sensörü
===========
![PTS](http://portal.parduslinux.org/wp-content/uploads/2015/04/pardus-logo2.png)
Gerekli Donanımlar
--------

 - Raspberry Pi (Pardus ARM Kurulu olarak)
 - WiringPi [(Kurulum Sayfası)](http://forum.pardus.net.tr/index.php?topic=3856)
 - DHT11 Sıcaklık ve Nem Sensörü
![enter image description here](http://docs.gadgetkeeper.com/download/attachments/7700673/dht11.jpg?version=1&modificationDate=1395550552000&api=v2&effects=border-simple,shadow-kn)
 - 4.7K veya 10K Direnç
![enter image description here](http://docs.gadgetkeeper.com/download/attachments/7700673/4.7k.jpg?version=1&modificationDate=1395550878000&api=v2&effects=border-simple,shadow-kn)
 - Breadboard
![enter image description here](http://docs.gadgetkeeper.com/download/attachments/7700673/breadboard.jpg?version=1&modificationDate=1395551116000&api=v2&effects=border-simple,shadow-kn)
 - Birkaç kablo
![enter image description here](http://docs.gadgetkeeper.com/download/attachments/7700673/jumper%20wires.jpg?version=1&modificationDate=1395551224000&api=v2&effects=border-simple,shadow-kn)

Bu proje IoT Projesi olup, Pardus ARM ekibi tarafından geliştirilmiştir. Bu proje sonunda ortamın sıcaklık ve nem bilgisini sensörden algılayabileceğiz.

Devrenin Kurulumu
------------
Devremizi şemada görüldüğü gibi yaptıktan sonra, Raspberry Pi üzerinde işlemler yapmaya başlayabiliriz.
![enter image description here](https://github.com/iscalik/iscalik.github.io/raw/master/DHT11/dht11_2.png)

Kullanımı
-----
dht11.c dosyasını indirdikten sonra, wiringPi ile derlememiz gerekiyor. Aşağıdaki komutu kullanarak C dosyasını derleyebiliriz.

    gcc -Wall -o dht11 dht11.c -lwiringPi

Derlemek bittikten sonra, programı açmak için yönetici izni ile aşağıdaki komutu kullanalım.

    ./dht11
Belirtilen işlemlerde sorun yok ise çıktı olarak şu bilgileri göreceksiniz.
![enter image description here](https://github.com/iscalik/iscalik.github.io/raw/master/DHT11/dht11_3.png)

***Destek***

İsmet Said Çalık 
<ismetsaid.calik@pardus.net.tr>
http://calik.me

Mehmet Nuri Öztürk
 <mehmetnuri.ozturk@pardus.net.tr>
 
Erdoğan Bilgici 
<destek@linuxcozumleri.com>
