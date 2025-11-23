# 📘 **Bilgisayar Bilimlerine Giriş — Kapsamlı Açıklamalı Özet**

Bu özet, tüm bölümlerdeki bilgileri tek bir akıcı anlatıda birleştirir.
Her kavramın yanında **neden önemli olduğu**, **nerede kullanıldığı** ve **bilgisayar bilimindeki yeri** detaylı olarak açıklanır.

---

# #️⃣ **Bölüm 0 — Giriş: Bilgisayar Bilimleri Neyi İnceler?**

Bilgisayar bilimi, sadece bilgisayar kullanmayı değil, **problemleri sistematik bir şekilde çözmeyi** öğretir. Bu bölümde amaç, temel kavramların ne olduğunu zihinde netleştirmektir.

## 🔹 Algoritmalar

Algoritma, belirli bir problemi çözmek için adım adım tanımlanmış işlemler dizisidir.
Bir yemek tarifi nasıl tam olarak ne yapacağımızı söylüyorsa, algoritmalar da programların ne yapacağını belirler.

## 🔹 Programlar

Program = algoritmanın bilgisayar tarafından anlaşılabilir hâle getirilmiş biçimi.
Bir algoritma yazılmadan program olmaz; program olmadan da bilgisayar “akıllı” davranamaz.

## 🔹 Tarihsel Gelişim

Abaküsten başlayan hesaplama tarihi, mekanik makineler, ENIAC gibi ilk bilgisayarlar ve sonunda kişisel bilgisayarlara kadar uzanır.
Bu tarihsel yolculuk, bugün kullandığımız cihazların nasıl evrildiğini ve neden böyle olduklarını anlamaya yardımcı olur.

## 🔹 Bilgisayar Biliminin Ana Alanları

Bu alanlar, bilgisayar bilimindeki bütün konuların temelini oluşturur:

* Algoritmalar
* Veri ve veri yapıları
* Abstraksiyon (karmaşık sistemleri basitleştirme)
* Programlama
* İnternet
* Etik

Her bölüm ileride yapacağın çalışmalarda tekrar tekrar karşına çıkacak.

---

# #️⃣ **Bölüm 1 — Veri Depolama: Bilgisayar Bilgiyi Nasıl Temsil Eder?**

Bilgisayarlar dünyayı bizim gibi görmez; onlar için her şey **0 ve 1**’dir. Bu bölüm, gerçek dünyanın bilgisayar tarafından nasıl temsil edildiğini açıklar.

## 🔹 Bit ve Bayt

* **Bit** → bilgisayarın saklayabildiği en küçük bilgi birimi
* **Bayt** → 8 bit’lik grup
  Bellek, milyonlarca bayttan oluşur ve her baytın benzersiz bir **adresi** vardır. Bu adres sayesinde bilgisayar veriyi bulur.

## 🔹 Bilginin Temsili

Bilgisayarın her tür bilgiyi saklaması için o bilginin **sayıya çevrilebilmesi** gerekir.

* Sayılar → doğrudan binary ile
* Metin → ASCII ve Unicode tabloları ile
* Görseller → piksel ve RGB değerleri ile
* Ses → dalgaların dijital örneklenmesiyle
* Video → ardışık görüntü kareleri ve ses birleşimi

Bu prensipleri bilmek, dosyaların neden farklı boyutlarda olduğunu anlamanı sağlar.

## 🔹 İkili Sistem (Binary)

Bilgisayarın kullandığı temel matematik sistemi.
Bu bölümde:

* 10’luk → 2’lik dönüşümler
* 2’lik sayıların toplanması
  gibi işlemleri öğrenerek bilgisayar mantığına bir adım daha yaklaşırsın.

## 🔹 Sayıların Bilgisayarda Temsili

* **Two’s complement** → negatif sayıların binary’de gösterimi
* **Floating point** → ondalıklı sayıların bilimsel gösterimi
  Bu yöntemler sayesinde bilgisayar hem tam hem ondalıklı sayılarla çalışabilir (ama bazen yuvarlama hataları oluşur).

## 🔹 Sıkıştırma ve Hata Kontrolü

Bilgiyi daha az yer kaplayacak şekilde kaydetmek için:

* JPEG → görüntü sıkıştırma
* MP3 → ses sıkıştırma
* Huffman → en sık kullanılan sembollere kısa kod verme
  Ayrıca iletim hatalarını bulmak için **parity bitleri** kullanılır.

---

# #️⃣ **Bölüm 2 — Veri İşleme: Bilgisayar Nasıl Çalışır?**

Bu bölüm, işlemcinin iç dünyasını anlamayı sağlar: bilgisayarın beyninde neler oluyor?

## 🔹 CPU ve Mimarisi

* **ALU** → Aritmetik işlemleri yapar (toplama, karşılaştırma vb.)
* **Kontrol birimi** → Komutların sırasını yönetir
* **Register’lar** → CPU içindeki küçük ve çok hızlı hafızalar
* **Bus** → bileşenlerin iletişim hattı

Bu parçaların birlikte çalışması, bilgisayarın tüm işlevlerinin temelidir.

## 🔹 Makine Kodu

Bilgisayar sadece makine kodunu (ikili komutları) anlar:

* LOAD
* STORE
* ADD
* JUMP

Komutlar genellikle **opcode + operand** şeklindedir.
RISC ve CISC mimarileri komutların karmaşıklığını belirler.

## 🔹 Komut Döngüsü

İşlemci her komutu şu sırayla işler:

1. **Fetch** → Komutu bellekten al
2. **Decode** → Komutun ne olduğunu çöz
3. **Execute** → Komutu çalıştır

Modern CPU’lar bu işlemleri pipeline gibi optimizasyonlarla hızlandırır.

## 🔹 Bit İşlemleri

AND, OR, XOR gibi işlemler birçok algoritmanın temelini oluşturur.
Kaydırma işlemleri özellikle şifreleme, grafik ve düşük seviye programlamada önemlidir.

## 🔹 Cihazlarla İletişim

Veri giriş çıkışı:

* Portlar
* DMA
* Seri ve paralel iletişim

Bunlar bilgisayarın dış dünya ile nasıl konuştuğunu açıklar.

## 🔹 Python ile Temel Programlama

Bu bölümde işlemcide olanları daha “insanca” anlatan yüksek seviyeli bir dil ile tanışırsın:

* Değişkenler
* Koşullar
* Döngüler
* Fonksiyonlar

## 🔹 Modern Mimariler

* Paralel işlem
* SIMD / MIMD sistemleri
* Komut boruhattı (pipeline)

Günümüzdeki işlemcilerin neden çok güçlü olduğunu anlamanı sağlar.

---

# #️⃣ **Bölüm 3 — İşletim Sistemleri: Bilgisayarın Görünmez Yöneticisi**

İşletim sistemi, bilgisayardaki her şeyi organize eden ana yazılımdır.

## 🔹 OS’in Görevleri

* Dosyaları yönetir
* Belleği düzenler
* Programların çalışmasını yönetir
* Donanımlarla iletişimi sağlar

Bilgisayar bu yönetim olmadan tamamen işlevsiz kalırdı.

## 🔹 Çalışma Modları

Örneğin:

* Gerçek zamanlı sistemler → fabrikalar, uçak kontrolü
* Çoklu görev → aynı anda birden fazla program
* Çoklu kullanıcı → sunucu sistemleri

Her mod farklı ihtiyaçlar için vardır.

## 🔹 OS Mimarisi

* **CLI/GUI** → kullanıcıyla iletişim kısmı
* **Kernel** → sistemin çekirdeği
* **Driver’lar** → donanımı çalıştıran kodlar

Bu katmanlı yapı, sistemi hem güçlü hem güvenli kılar.

## 🔹 Süreç Yönetimi

Her çalışan program bir **process**’tir.
OS bu süreçlere CPU zamanını adil bir şekilde dağıtır.

## 🔹 Deadlock ve Senkronizasyon

Çoklu işlem yapan sistemlerde:

* deadlock → iki sürecin birbirini bekleyip sonsuza dek tıkanması
* critical section → paylaşılan verinin korunması
* semaforlar → düzenleyici mekanizma

Bu konular yazılımın güvenli çalışması için kritiktir.

## 🔹 Güvenlik

OS hem iç hem dış tehditlere karşı koruma sağlar:

* malware
* yetkisiz erişimler
* şifreleme

---

# #️⃣ **Bölüm 4 — Ağ ve İnternet**

Bu bölüm, bilgisayarların birbirine nasıl bağlandığını ve İnternet’in nasıl çalıştığını açıklar.

## 🔹 Ağ Türleri

* **PAN** → kişisel alan
* **LAN** → yerel ağ (ev/okul)
* **MAN** → şehir çapı
* **WAN** → ülke/okyanus aşırı bağlantılar

## 🔹 Protokoller

Ethernet (CSMA/CD) ve Wi-Fi (CSMA/CA) verinin çarpışmadan iletilmesini sağlar.

## 🔹 Ağ Cihazları

* Repeater → sinyal güçlendirici
* Switch → çerçeveleri hedef cihazlara yönlendirir
* Bridge → ağ bölümlerini bağlar
* Router → IP paketlerini başka ağlara yollar

## 🔹 İnternet’in Çalışması

* ISP katmanları
* IP adresleri
* DNS → alan adını IP’ye çevirir

## 🔹 Temel Protokoller

* HTTP, SMTP, FTP, SSH
* E-posta: POP3 / IMAP

## 🔹 WWW ve Web Teknolojileri

* URL
* HTML / XML
* İstemci–sunucu modeli
* P2P sistemler

## 🔹 TCP/IP Modeli

TCP → güvenli, sıralı iletim
UDP → hızlı, ama garanti yok

## 🔹 Güvenlik

* HTTPS
* DoS saldırıları
* Anahtar tabanlı şifreleme

---

# #️⃣ **Bölüm 5 — Algoritmalar: Problemleri Sistematik Çözmek**

Bu bölüm programlamanın temel mantığını öğretir.

## 🔹 Algoritma Nedir?

Kesin, sonlu ve mantıklı adımlardan oluşan çözüm tarifidir.

## 🔹 Algoritmalar Nasıl Yazılır?

* Primitif işlemler
* Koşullar
* Döngüler
* Fonksiyonlar
* Pseudocode

## 🔹 Algoritma Tasarımı

“Pólya Metodu”:

1. Problemi anla
2. Plan yap
3. Uygula
4. Kontrol et

Bu, gerçek hayatta her problemde kullanılabilir.

## 🔹 Temel Algoritmalar

* Doğrusal arama
* İkili arama
* Ekleme sıralaması

## 🔹 Özyineleme (Recursion)

Bir problemin kendisinin daha küçük versiyonuyla çözülmesi.
Hanoi Kuleleri bunun klasik örneğidir.

## 🔹 Verimlilik (Big-Θ)

Aynı işi yapan iki algoritma çok farklı hızlarda olabilir.
Big-Θ notasyonu bunu matematiksel olarak anlatır.

---

# #️⃣ **Bölüm 6 — Programlama Dilleri**

Bu bölüm, dillerin nasıl çalıştığını kavramanı sağlar.

## 🔹 Dillerin Seviyeleri

* Makine kodu
* Assembly
* Yüksek seviyeli diller (Python, C++, Java…)

## 🔹 Çeviri Süreçleri

* **Derleyici** (compiler) → yüksek seviyeli kodu makine koduna çevirir
* **Yorumlayıcı** (interpreter) → kodu satır satır çalıştırır
* **Parser** ve **AST** → kodun yapısal analizi

## 🔹 Temel Kavramlar

* Değişkenler
* Türler
* Kontrol yapıları
* Fonksiyonlar

## 🔹 Programlama Paradigmaları

### **Prosedürel**

Adım adım komutlarla ilerleyen yapı.

### **Nesne Yönelimli Programlama (OOP)**

* Sınıflar
* Nesneler
* Metodlar
* Kalıtım
* Kapsülleme
* Polimorfizm

Modern dillerin çoğu bu paradigmayı kullanır.

---

# #️⃣ **Bölüm 7 — Yazılım Mühendisliği**

Bu bölüm, sadece kod yazmayı değil **büyük yazılım projelerinin nasıl geliştirildiğini** öğretir.

## 🔹 Yazılım Geliştirme Yaşam Döngüsü (SDLC)

1. Gereksinim analizi
2. Tasarım
3. Kodlama
4. Test
5. Bakım

## 🔹 Geliştirme Metodolojileri

* Waterfall
* Agile
* Prototipleme
* İteratif geliştirme

Agile günümüzde en yaygın kullanılan yaklaşımdır.

## 🔹 Modelleme Araçları

* UML diyagramları
* ER diyagramları
* Veri akış diyagramları

Bu araçlar büyük sistemlerin planlanmasını kolaylaştırır.

## 🔹 Kalite, Test ve Dokümantasyon

Yazılımın güvenilir olması için testler ve iyi belgeler şarttır.

---

# #️⃣ **Bölüm 8 — Yapay Zekâ**

Bu bölüm, günümüz dünyasını şekillendiren yapay zekânın temellerini açıklar.

## 🔹 Akıllı Ajanlar

Bir sistemin çevreyi algılayıp hedefe uygun davranış üretmesi.
Tepki temelli, hedef temelli ve öğrenen sistemler gibi seviyeleri vardır.

## 🔹 Turing Testi

Bir makinenin “insan gibi düşündüğünü” test eden yöntem.

## 🔹 Algılama

* Görüntü işleme (edge detection)
* Doğal dil işleme (NLP)

## 🔹 Akıl Yürütme ve Arama

* Durum ağaçlarında arama
* Mantık sistemleri

## 🔹 Öğrenme Yöntemleri

* Supervised learning
* Imitation learning

## 🔹 Genetik Algoritmalar

Doğal evrim süreçlerini taklit ederek çözüm arayan yöntemler.

## 🔹 Yapay Sinir Ağları

* Perceptron
* Gizli katmanlar
* Geri yayılım (backpropagation)

## 🔹 Uygulamalar

* Otonom araçlar
* Görüntü tanıma
* Robotik

---

# 🎉 **Sonuç**

Bu tek dosyalık özet, tüm bölümlerdeki bilgileri **açıklamalı, bağlamlı ve akıcı bir dille** bir araya getirmiştir.
Artık her kavramın:

* ne olduğu,
* neden önemli olduğu,
* nerede kullanıldığı
  net bir şekilde anlaşılır durumda.

