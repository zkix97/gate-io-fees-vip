# gate io komisyon oranları: güncel VIP tablosu, GT indirimi ve komisyonu düşürme yolları

Kısa cevap: Gate'te standart seviyede (VIP0) spot işlem komisyonu maker ve taker tarafında **%0,10 / %0,10**. Vadeli işlemlerde bu oran maker %0,02, taker %0,05'e iniyor. İşlem ücretini GT (GateToken) ile ödemeyi açarsanız spot tarafı %0,09'a düşüyor.

Bu iki satırdan sonrası asıl mesele: hangi seviyede ne ödediğiniz, o seviyeye çıkmak için ne gerektiği, para çekmenin ne kadara mal olduğu ve Türkiye tarafında TL akışının nasıl işlediği.

Türkçe kaynaklarda sık tekrarlanan "%0,2" rakamına da baştan açıklık getirelim: o oran Gate'in eski tarifesinden kalma. Ücret tablosu Nisan ayı başında güncellendi ve VIP0 spot oranı şu an %0,10. Elinizdeki bir karşılaştırma yazısı %0,2 diyorsa, muhtemelen güncellenmemiş bir sayfaya bakıyorsunuz.

## Maker ve taker: iki oran, iki farklı davranış

Gate'in komisyon sistemi tek bir rakam değil, iki farklı rol üzerine kurulu.

- **Maker:** Emir defterine, anında eşleşmeyen bir emir bırakan taraf. Piyasaya likidite eklediği için daha düşük ücret öder.
- **Taker:** Defterde zaten bekleyen bir emirle anında eşleşen taraf. Likidite tükettiği için daha yüksek ücret öder.

Pratikte bu şu demek: piyasa emri verirseniz taker, fiyat belirtip beklemeye bırakırsanız maker tarafındasınız. VIP0'dan VIP3'e kadar iki oran aynı olduğu için beklemek size hiçbir şey kazandırmıyor. Ayrım ilk kez VIP4'te açılıyor (%0,095 maker, %0,096 taker) ve yukarı çıktıkça makas büyüyor.

Sık yapılan bir hesap hatası: komisyonu sadece giriş işleminde hesaplamak. Bir tur alım-satımda iki kez ücret ödersiniz. 1.000 USDT'lik bir pozisyonu VIP0'da alıp satmak size yaklaşık 2 USDT'ye mal olur — kâr edip etmediğinizi hesaplarken bu kalemi atlamak kolay.

## Tüm VIP seviyeleri: Gate komisyon oranları tablosu

Gate, VIP0'dan VIP16'ya kadar 17 kademe kullanıyor. Aşağıdaki tablo, Gate'in resmi ücret sayfasındaki güncel spot oranlarını gösteriyor. 30 günlük işlem hacmi sütunu, o seviyeye çıkmanın hacim tarafındaki eşiği.

| VIP seviyesi | 30 günlük işlem hacmi (USD) | Spot maker | Spot taker | GT ile ödeme | Kayıt |
| --- | --- | --- | --- | --- | --- |
| VIP0 | 0 | %0,100 | %0,100 | %0,090 / %0,090 | [ Hesap aç](https://bit.ly/GateVIP) |
| VIP1 | 60.000 | %0,099 | %0,099 | %0,089 / %0,089 | [ Ücretsiz kayıt](https://bit.ly/GateVIP) |
| VIP2 | 120.000 | %0,098 | %0,098 | %0,088 / %0,088 | [ Kaydını tamamla](https://bit.ly/GateVIP) |
| VIP3 | 240.000 | %0,097 | %0,097 | %0,087 / %0,087 | [ Hesap aç](https://bit.ly/GateVIP) |
| VIP4 | 500.000 | %0,095 | %0,096 | %0,086 / %0,086 | [ Ücretsiz kayıt](https://bit.ly/GateVIP) |
| VIP5 | 1.000.000 | %0,090 | %0,095 | %0,081 / %0,085 | [ Kaydını tamamla](https://bit.ly/GateVIP) |
| VIP6 | 3.000.000 | %0,085 | %0,090 | %0,076 / %0,081 | [ Hesap aç](https://bit.ly/GateVIP) |
| VIP7 | 8.000.000 | %0,080 | %0,085 | %0,070 / %0,076 | [ Ücretsiz kayıt](https://bit.ly/GateVIP) |
| VIP8 | 20.000.000 | %0,075 | %0,080 | %0,060 / %0,072 | [ Kaydını tamamla](https://bit.ly/GateVIP) |
| VIP9 | 50.000.000 | %0,070 | %0,075 | %0,050 / %0,068 | [ Hesap aç](https://bit.ly/GateVIP) |
| VIP10 | 100.000.000 | %0,040 | %0,058 | GT indirimi yok | [ Ücretsiz kayıt](https://bit.ly/GateVIP) |
| VIP11 | 120.000.000 | %0,030 | %0,045 | GT indirimi yok | [ Kaydını tamamla](https://bit.ly/GateVIP) |
| VIP12 | 240.000.000 | %0,020 | %0,037 | GT indirimi yok | [ Hesap aç](https://bit.ly/GateVIP) |
| VIP13 | 440.000.000 | %0,010 | %0,030 | GT indirimi yok | [ Ücretsiz kayıt](https://bit.ly/GateVIP) |
| VIP14 | 800.000.000 | %0,008 | %0,023 | GT indirimi yok | [ Kaydını tamamla](https://bit.ly/GateVIP) |
| VIP15 | 1.600.000.000 | %0,000 | %0,020 | GT indirimi yok | [ Hesap aç](https://bit.ly/GateVIP) |
| VIP16 | 3.000.000.000 | %0,000 | %0,0175 | GT indirimi yok | [ Ücretsiz kayıt](https://bit.ly/GateVIP) |

Tabloda iki şey dikkat çekiyor.

Birincisi, VIP0 ile VIP1 arasındaki fark neredeyse yok: %0,100'den %0,099'a, yani 100.000 USDT'lik bir işlemde 1 USDT. Seviye atlamak uğruna hacim şişirmek mantıklı bir strateji değil.

İkincisi, VIP10'dan sonra GT indirimi kayboluyor. Alt seviyelerde GT ile ödeme yaklaşık %10 tasarruf sağlarken, VIP10 ve üzerinde iki sütun aynı rakamı gösteriyor. Yani ücretin en çok önemli olduğu yerde token bir avantaj sunmuyor.

> Not: Oran tablosu zaman zaman güncelleniyor ve tablonun üst kısmıyla alt kısmı farklı tarihlerde revize edilmiş olabiliyor. İşlem yapmadan önce hesabınıza giriş yaptığınızda görünen kendi ücret oranınızı esas alın — hesabınıza özel oran, tablodaki standart orandan farklı olabilir.

## VIP seviyesi nasıl yükseliyor?

Seviyenizi üç kanaldan biri belirliyor ve sistem en yükseğini uyguluyor:

1. **30 günlük toplam işlem hacmi** — spot ve hisse senedi hacimleri %100 sayılıyor. USDT perpetual, BTC perpetual ve USDT vadeli kontratlar %40, USD1 kontratları ve opsiyonlar %20, CFD kontratları %10 ağırlıkla hesaba katılıyor.
2. **14 günlük ortalama GT varlığı** — cüzdan, marjin ve Earn ürünlerindeki GT bakiyesinin günlük ortalaması.
3. **VIP yükseltme varlık değeri** — hesabınızdaki toplam varlık. VIP1 için 2.000 USD, VIP5 için 40.000 USD, VIP10 için 2.000.000 USD seviyesinde.

Hacim ağırlıklandırması kulağa teknik geliyor ama etkisi basit: aynı büyüklükte işlem yapan iki kişiden vadeli tarafında işlem yapan, spot tarafında işlem yapanın yaklaşık yarısı kadar hacim biriktirir. Vadeli işlemleri spotla aynı kefeye koyan karşılaştırmalar yanıltıcı.

Kademe artışı otomatik. Başvuru yok, ayrı bir ücret yok.

## Vadeli işlemlerde komisyon: teminat değil, pozisyon büyüklüğü

Gate'in vadeli ücretleri spot tarafından çok daha düşük ve yapı da farklı. USDT teminatlı perpetual kontratlarda VIP0 oranları maker %0,02, taker %0,05. Aşağı indikçe VIP16'da maker %0'a, taker %0,016'ya kadar geriliyor.

Burada en çok karıştırılan nokta, ücretin neyin üzerinden hesaplandığı. Komisyon, yatırdığınız teminat üzerinden değil, **pozisyonun toplam büyüklüğü** üzerinden alınıyor ve kaldıraç bu hesabı değiştirmiyor.

Örnek: 60.000 USD değerinde bir pozisyon açıyorsunuz. Piyasa emriyle girerken taker oranı %0,05 ise ödediğiniz ücret 30 USD. Aynı pozisyonu limit emirle açıp eşleşmeyi beklerseniz maker oranı %0,02 üzerinden 12 USD. Aradaki 18 USD, sadece emir tipini değiştirmenin karşılığı.

Ücret pozisyon açılırken, kapanırken veya kısmen azaltılırken alınıyor. Verilmeyen ya da iptal edilen emirlerden ücret çıkmıyor.

Vadeli tarafta komisyondan ayrı bir kalem daha var: **fonlama ücreti**. Perpetual kontratlarda genellikle 8 saatte bir, long ve short pozisyonlar arasında ödenen bir tutar; Gate'in kazancı değil. Gün içi işlem yapıyorsanız etkisi küçük, pozisyonu günlerce taşıyorsanız işlem komisyonunu rahatlıkla geçebilir. Marjin borçlanma faizi de ayrı bir kalem ve kullandığınız varlığa, süreye ve piyasaya göre değişiyor.

## GT indirimi gerçekte kaç para kazandırıyor?

GT ödemeyi açtığınızda spot oranı VIP0'da %0,10'dan %0,09'a iniyor. Yüzde 10'luk bir indirim gibi görünüyor, öyle de. Ama mutlak rakama bakalım: aynı gün içinde 10.000 USDT'lik bir pozisyonu alıp satan biri, standart oranda yaklaşık 20 USDT, GT indirimiyle yaklaşık 18 USDT öder. Kâr 2 USDT.

Aylık 1.000.000 USDT hacme çıktığınızda fark 100 USDT'yi buluyor — orada ciddi bir kalem haline geliyor. Yani GT indirimi aktif trader'ın işine yarar, ayda birkaç işlem yapan biri için sembolik kalır.

Açmak için: hesap ayarlarındaki ücret bölümünden "GT ile öde" seçeneğini aktif ediyorsunuz. GT bakiyeniz yetmediğinde sistem otomatik olarak VIP oranınıza dönüyor, işlem reddedilmiyor.

Burada iki kısıt var. GT indirimi ile puan kartı (point card) aynı anda kullanılamıyor. Puan kartı tarafında spot ücret sabit %0,2, vadeli taker ücreti sabit %0,075 olarak uygulanıyor — yani VIP0'daki standart orandan yüksek. Puan kartı ancak yüksek VIP seviyelerinde mantıklı hale geliyor, düşük seviyelerde hesabınıza zarar yazabilir.

## Yatırma, çekme ve Türkiye tarafı

Kripto para yatırma Gate tarafında ücretsiz: hesabınıza gelen on-chain transferler için platform komisyon almıyor. P2P üzerinden yapılan yatırmalar da ücretsiz.

Çekim tarafı ise sabit bir rakam değil. Çekim ücreti seçtiğiniz coin ve blokzincir ağına göre değişiyor ve ağ yoğunluğuna bağlı olarak yaklaşık saatlik güncelleniyor. Çekim ekranında coin ve ağı seçtiğinizde ücret ile minimum çekim tutarı görünür. TRX veya katman-2 ağları gibi daha ucuz seçenekler maliyeti belirgin şekilde düşürüyor. Aynı coinin farklı ağları arasındaki fark, bazen işlem komisyonundan büyük olur; çekim yapmadan önce ağ seçimini bir kez daha kontrol etmeye değer.

Türkiye'de iki ayrı kullanım yolu var ve komisyon tablosu ikisinde de aynı değil:

- **Gate TR (TL ağırlıklı):** TL yatırma ve çekme işlemleri için asıl rota burası. TL gönderimi yalnızca kendi adınıza kayıtlı bireysel banka hesabından yapılabiliyor. ATM veya kredi kartıyla TL transferi kabul edilmiyor; Papara, Paycell gibi üçüncü taraf ödeme servisleri de kabul edilmiyor. TL çekim hızı bankaya göre değişiyor — bazı bankalarda 7/24, bazılarında mesai saatleriyle sınırlı.
- **Gate.com global (P2P ve kart):** Global hesapta TL banka havalesi yerine P2P ve kartla kripto alımı öne çıkıyor. Kartlı alımlarda ödeme sağlayıcısının komisyonu ve yere göre değişen yerel vergiler maliyete ekleniyor; bu tutar Gate'in işlem komisyonundan bağımsız.

Global hesapta işlem yapacaksanız yukarıdaki VIP tablosu geçerli. TL ile doğrudan alım-satım yapacaksanız Gate TR'nin kendi ücret sayfasına bakmanız gerekir, çünkü ayrı bir platform ve oranları ayrı yayınlanıyor.

## Diğer ürünlerde ücretler

Komisyon denince akla ilk spot ve vadeli geliyor ama Gate'in tablosunda başka kalemler de var:

- **Alpha (zincir üstü) işlemler:** Tüm VIP seviyelerinde sabit **%0,8**.
- **Opsiyonlar:** Maker ve taker %0,03, kullanım (exercise) ücreti %0,02.
- **Gate Stocks:** ABD hisse ve ETF'lerinde uygun ürünler için sıfır işlem komisyonu, sıfır hesap açma ücreti ve sıfır minimum işlem ücreti uygulanıyor. Üçüncü taraf takas ve düzenleyici ücretleri bunun dışında kalıyor. Program dışındaki işlemlerde VIP0 için %0,1 seviyesinden başlayan kademeli yapı geçerli.
- **CFD:** Forex, kıymetli maden, emtia ve endeks kontratlarında işlem komisyonu artı pozisyon gün sonunu geçtiyse swap ücreti alınıyor.

Zincir üstü tarafı ayrıca not edelim: %0,8, merkezi borsa oranlarıyla kıyaslandığında yüksek görünür ama bu işlemlerin maliyet yapısı farklı. Etiket oranına bakıp "Gate pahalı" sonucuna varmak yanlış olur; hangi üründe işlem yaptığınıza bakmanız gerekir.

## Komisyonu düşürmenin yolları

Etiket oranını değiştiremezsiniz, ama ödediğiniz tutarı etkileyen birkaç kaldıraç var:

1. **Limit emir kullanın.** VIP4'ten itibaren maker oranı taker'dan düşük. Alış fiyatınızı yazıp beklemek, tek seferde birkaç baz puan kazandırır.
2. **GT indirimini açın.** Maliyeti yok, kapatmanın bir sebebi de yok — tabii GT bakiyenizi düzenli tutuyorsanız.
3. **USDC/USDT paritesini kullanın.** Bu parite ücretsiz işlem görüyor, yani dolar bakiyenizi USDT'den USDC'ye çevirmenin ek maliyeti yok.
4. **Kayıt bağlantısındaki komisyon iadesini kullanın.** Gate'in davet programı, davet edilen kişinin ödediği işlem komisyonunun bir kısmının geri ödenmesine dayanıyor. Oran kayıt sırasında girilen koda bağlı ve hesabınız açıldıktan sonra değiştirilemiyor.

   [👉 Davet bağlantısıyla Gate hesabı aç](https://bit.ly/GateVIP)

   Kesin iade oranınızı varsayımla değil, hesabınızın ödül/komisyon bölümünden teyit edin. Kayıt tamamlandıktan sonra kod ekleme veya kodu değiştirme imkânı yok; bu yüzden kaydı doğru bağlantı üzerinden başlatmak önemli.
5. **Çekim ağını bilinçli seçin.** Ethereum yerine TRX veya katman-2, birkaç dolarlık fark yaratır.
6. **Hacim şişirmeyin.** Seviye atlamak için ekstra işlem yapmak, kazandığınız komisyon farkından daha fazlasını spread ve fonlama ücretlerinde geri verir. Traders Union gibi kaynaklar da aynı uyarıyı yapıyor.

## Rakamlarla kısa bir karşılaştırma

Traders Union'un Nisan ayındaki karşılaştırmasında Gate'in standart spot oranı %0,10 / %0,10 olarak görünüyor; Binance'te de aynı, Kraken'de maker %0,25 taker %0,40 seviyesinde. Vadeli tarafta Gate 0,02 / 0,05 ile Binance ve Kraken ile aynı çizgide.

Yani başlangıç seviyesinde Gate ne belirgin şekilde ucuz ne de pahalı; sektörün alt-orta bandında konumlanıyor. İki şeyi ayırıyor: 3.800'ün üzerinde spot işlem çifti ve 17 kademeli VIP tablosu. Yeni listelenen küçük tokenlara erken erişmek isteyenler için bu ilk kalem, yüksek hacimle işlem yapanlar için ikincisi daha önemli.

Bir uyarı: bazı karşılaştırma siteleri Gate için hâlâ %0,2 gösteriyor. Bu rakam eski tarifeden geliyor ve iki katı hata payı yaratıyor. Karşılaştırma okurken tablonun hangi tarihte doğrulandığına bakın.

## Sık sorulan sorular

### Gate.io komisyon oranları ne kadar?

VIP0'da spot işlemlerde maker ve taker %0,10 / %0,10. GT ile ödeme açıkken %0,09 / %0,09. USDT teminatlı vadeli kontratlarda maker %0,02, taker %0,05. Seviye yükseldikçe oranlar düşüyor, VIP16'da spot maker %0'a ve vadeli taker %0,016'ya kadar iniyor.

### Türkiye'den Gate kullanılıyor mu?

Kullanılıyor, ama iki farklı yol var. TL yatırma-çekme işlemleri Gate TR üzerinden, kendi adınıza kayıtlı banka hesabından yapılıyor. Global hesapta işlem yapacaksanız P2P ve kartlı alım seçenekleri öne çıkıyor. Bölgeye göre kampanya ve davet programı kapsamı değişebiliyor; kayıt ekranında size uygulanan koşullar görünüyor.

### Komisyon indirimi kalıcı mı?

Davet kodu üzerinden tanımlanan komisyon iadesi, kod kayıt sırasında girildiği sürece hesabınıza kalıcı olarak bağlanıyor; her ay yeniden girmeniz gerekmiyor. Ancak oranı kayıt sonrasında değiştirmek mümkün değil, bu yüzden [👉 kayıt sayfasını açmadan önce](https://bit.ly/GateVIP) kodu alanın dolu geldiğini kontrol edin.

### Çekim ücreti ne kadar?

Coin ve ağa göre değişiyor, sabit bir rakam yok. Çekim ekranında seçim yaptığınızda ücret ve minimum tutar anında görünüyor. Ucuz bir ağ seçmek toplam maliyeti tek başına ciddi biçimde düşürebilir.

### Para yatırmak ücretli mi?

Kripto yatırma Gate tarafında ücretsiz, P2P üzerinden yapılan yatırmalar da ücretsiz. Kartlı alımlarda ödeme sağlayıcısının komisyonu ve yerel vergiler maliyete ekleniyor.

## Kısaca

Gate'in komisyon tablosunda bakılacak üç sayı var: VIP0 spot oranı (%0,10), vadeli taker oranı (%0,05) ve GT indiriminin sizi götürdüğü seviye (%0,09). Geri kalan 16 kademe, çoğu kullanıcı için ulaşılması zor eşiklerle ayrılmış durumda — VIP1'e çıkmak için 60.000 USD'lik 30 günlük hacim ya da 2.000 USD varlık gerekiyor.

Aylık birkaç bin dolarlık işlem yapıyorsanız en gerçekçi tasarruf kalemleri GT indirimi, limit emir kullanımı ve kayıt sırasında bağlanan komisyon iadesi. Yüksek hacimli çalışıyorsanız asıl fark vadeli tarafta ve VIP kademelerinde açılıyor.

[👉 Güncel oranlarla Gate hesabınızı açın](https://bit.ly/GateVIP)
