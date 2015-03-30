# Ghostone-2.0-Version-Weplaes-By-Pro_wamp
Türkçe ghostone 2.0 version

Ghostone 2.0 Version @ WEplaes By Pro_wamp

Güncellemeler;

1* Addban komutu düzenlendi. Bir oyuncunun ban süresi bilgisayarın tarih saatine göre ayarlandı. Eskiden Sadece tarih alıyordu saati 00.00 olarak alıyordu. Ban sona erme süresine saat eklendi. +

Eskiden ;

!addban <nick>     = 
id	botid	     server             name	   ip	               date	       gamename	         admin	   reason	gamecount	expiredate	   warn
3	0	bnet.weplaes.com	test2	127.0.0.1	2015-03-25   	      Ghostone 2.0	pro_wamp    test	    0	    2015-03-27 	    	    0 

Şimdi:

!addban <nick>     = 
id	botid	     server             name	   ip	               date	       gamename	         admin	   reason	gamecount	expiredate	   warn
3	0	bnet.weplaes.com	test2	127.0.0.1	2015-03-25 16:44:54   Ghostone 2.0	pro_wamp    test	    0	    2015-03-27 16:44:54	    0 


2* Otomatik ban suresi 'bot_bantime = 'e göre otomatik olarak ayarlanıyor. +
3* Bot %95 türkçeleştirildi. +
4* Oyuna başlama geri sayim saniyesi '10' olarak değiştirildi. +
5* Welcome.txt düzenlendi; +

$OWNERNAME$ , $GAMENAME$ , $USER$ eklendi.

Bkz;

Hosgeldin : $USER$
Oyun ismi : $GAMENAME$ Oyun Sahibi : $OWNERNAME$

Hosgeldin : pro_wamp
Oyun ismi : TEST       Oyun Sahibi : pro_wamp 

Welcome.txt'yi arayüzden dilediğiniz gibi düzenleyebilirsiniz.

6* Baştan savma yapilan Turkish.cfg düzenlendi. +
7* Lobbytimelimit dakika yerine saat olarak değiştirildi. +
8* Replay Builder 1.26 Patch olarak değiştirildi. +
9* Weplaes icin tanimlama olayi fixlendi. +
10* RMK komutu ve WHORMK komutu eklendi.  +
11* %100 istatistik tutan FF komutu ve WHOFF komutu eklendi. +
12* Minff Suresi eklendi. Ghost.cfg bot_minff = 'den ayarlayabilirsiniz. +
13* Checkme ve check komutu düzenlendi. owner ve spoofcheck yerleri kaldirildi , client acik olup olmadiği eklendi. +
14* Sameip komutu eklendi. +
15* Client komutu eklendi. +
16* kurallar / rules komutu eklendi. +
17* muteall <nick> komutu eklendi. +
18* votemute eklendi. +
19* votestart patch eklendi. -
20* Oyun girişlerinde gösterilen istatistik sda olarak değiştirildi. +
21* sd komutu düzenlendi. Win Lose eklendi ve tüm kullanıcılar kullanabilir. +
22* statsdota komutu sda olarak değiştirildi ve . Score , rank eklendi. tüm kullanicilar kullanabilir. +
23* colorednames.txt eklendi. +
24* AB / Balance komutu eklendi ! +
25* CB Komutu eklendi ve tum kullanicilar kullanabilir. +
26* Score komutu eklendi ve tüm kullanıcılar kullanabilir. +
27* Scores komutu eklendi ve tüm kullanıcılar kullanabilir. +
28* Trade-Hack tespit edici eklendi. +


Kullanım;

colorednames.txt 'ye yazcağınız nick ve renkodu nickle oyununuza giren arkadaşlarınız veya sizin isminizi renkli yapabilirsiniz.

Bkz:

pro_wamp 00FF00WaMP yazdığımızda pro_wamp nicki Yesil Renkte WaMP olarak görükecektir. Yazacağınız nicklerin küçük harfli olduğuna dikkat ediniz. Renk kodlarını ghostoneden alabilirsiniz.

29* Gamelist Patch eklendi. +
30* !Games komutu eklendi. +

31* sqlite3 database için bot formula değiştirildi. Yeni oyun oynayan kullanıcıların ratingleri 1500 olarak ayarlandı ve kazanma durumunda +10 rating , kaybetme durumunda -5 rating kaybedecek. Oynadığı oyun
sayısına göre kullanıcılar 0.2 fazla rating kazacaktır. +

32* %100 Türkçe istatistik web sitesi eklendi.
33*




Komutlar İşlevleri;

!RMK = RMK oylaması başlatır. 2 takımda oy verirse oylama sonuçlanır oyun kapanır ve rmk açılır. +
!WHORMK = RMK Oy sayıcını gösterir. +
!FF = Komutu yazan takim için FF(forfeit) oylaması başlatır. Oylama sonuçlanırsa takım hükmen yenilmiş sayılır ve diğer takım oyunu kazanır. Oyun otomatik olarak kapanır.+
!WHOFF = FF oy sayını gösterir. +
!SAMEIP = Ayni ip'den giriş yapmış oyuncuları gösterir. +
!CLIENT = Bulunduğunuz serverın clientinden giriş yapmış oyuncuları gösterir. +
!GN = Mevcut oyun ismini gösterir. +
!sCORE = Mevcut ratinginizi gösterir. +
!SCORES = Takım oyuncularının ratinglerini gösterir. +
!IGNOREALL = Butun oyuncuların yazışmaları siz için yok sayılır. Yani hiç birinin yazdığını okuyamazsınız. Tekrar aynı komutu yazdığınızda düzelir. +
!KURALLAR / !RULES = Komut Ghostone 2.0 klasöründe bulunan kurallar.txt dosyasındaki yazdığınız kuralları ALLCHAT'tan yazar. +
!VOTEMUTE <nick> = Oyuncu için mute oylaması başlatır. Oylama sonuçlanırsa oyuncu 1 oyunluk mutelenir. +
!BALANCE/!AB = 2 takimin rating ortlamasını eşitler. +
!CB = Takim ortlama ratingini gösterir. +
!SCORE = Ratinginizi ve Rankinizi gösterir. +
!SCORES = Oyuncuların sırayısla ratinglerini gösterir. +

 Sqlite3'te bazı komutlarda sorun olabilir. Bkz: !ab !cb !score !scores . Mysql database kullanmanızı tavsiye ederim. 

 Mysql database için wampserver kurmanızı öneririm kullanımı gayet kolay ve basit arayüzü var.

