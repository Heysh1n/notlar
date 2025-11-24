# Bilgisayar Bilimine Giriş  
**13. Baskı, Global Edition** – J. Glenn Brookshear & Dennis Brylow  
*Sınav için kısa notlar*

## Bölüm 0 – Giriş
- **0.1 Algoritmaların rolü**  
  Algoritma → görevi adım adım açıklayan talimatlar  
  Program → algoritmanın gösterimi  
  Yazılım → programlar + algoritmalar  
  Donanım → fiziksel kısım
- **0.2 Hesaplamanın tarihçesi**  
  Abaküs → dişli makineler → ENIAC → IBM PC → İnternet & akıllı telefonlar
- **0.3 Dersin kapsamı**  
  1 Veri Depolama │ 2 Veri İşleme │ 3 İşletim Sistemleri │ 4 Ağlar │ 5 Algoritmalar │ 6 Programlama Dilleri │ … │ 11 Yapay Zeka
- **0.4 7 büyük tema**  
  Algoritmalar – Soyutlama – Yaratıcılık – Veri – Programlama – İnternet – Etki

## Bölüm 1 – Veri Depolama
- 1.1 Bit (0/1) → her şey bit desenidir
- 1.2 Ana Bellek (RAM) – hücre = 8 bit (1 bayt)
- 1.3 Yığın Depolama (disk, SSD) – kalıcı, büyük, ucuz
- 1.5 İkilik sistem (binary)
- 1.6 Tam sayılar → İkinin tümleyeni (two’s complement)
- 1.7 Kesirli sayılar → Kayan nokta (floating point)
- 1.9 Veri sıkıştırma → kayıplı/kayıpsız (JPEG, ZIP)
- 1.10 İletişim hataları → eşlik biti (parity bit)

## Bölüm 2 – Veri İşleme
- **2.1 Bilgisayar mimarisi**  
  CPU (ALU + Kontrol + Yazmaçlar) + Veriyolu + Ana Bellek
- 2.2 Makine dili → opcode + operand
- 2.3 Program yürütme → fetch-decode-execute döngüsü
- 2.4 Mantık işlemleri → AND, OR, XOR, kaydırma
- 2.7 Diğer mimariler → pipelining, çok işlemcili sistemler

## Bölüm 3 – İşletim Sistemleri
### 3.1 Tarihçe
Batch → etkileşimli → zaman paylaşımı → çok görevli → gömülü sistemler

### 3.2 Mimari
- **Kernel** → dosya yöneticisi, bellek yöneticisi, zamanlayıcı, aygıt sürücüleri
- **Kullanıcı arayüzü** → shell veya GUI
- **Booting** → ROM’daki önyükleyici → İşletim sistemini RAM’e yükler

### 3.3 İşlem (process) yönetimi
- İşlem = çalışan program
- Zamanlayıcı (scheduler) + sevk edici (dispatcher)
- Çoklu programlama

### 3.4 Yarış (race condition) ve kilitlenme
- Semafor → kritik bölgeyi korur
- Deadlock → iki işlem birbirinin kaynağını bekler

### 3.5 Güvenlik
- Dış saldırılar → zayıf şifre, sniffing
- İç saldırılar → bellek taşması

### İşletim Sistemi Örnekleri
- Windows, macOS, Linux, UNIX, Android, iOS

---

**İpucu:** Sınavda en çok sorulanlar  
- Algoritma tanımı  
- Two’s complement  
- CPU bileşenleri  
- Deadlock örneği  
- İşletim sistemi görevleri  
- Booting sırası

Başarılar!
