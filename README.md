# calisma-notlarim
ALGORİTMA VE YAZILIM ÖĞRENİM NOTLARIM
1. Algoritma Nedir?
Bir sorunu çözmek veya bir amaca ulaşmak için tasarlanan adım adım yol haritasıdır. Yazılımın temelidir.

2. Temel Kavramlar:

Değişkenler: Programda verileri (isim, sayı, tarih) geçici olarak sakladığımız kutulardır.

Karar Yapıları (If-Else): Programın belirli şartlara göre yol ayrımına girmesidir. (Örneğin: Ödeme yapıldı mı? Evetse devam et, Hayırsa dur.)

Döngüler (Loops): Belirli bir işlem tamamlanana kadar aynı adımların otomatik olarak tekrar edilmesidir.

3. Çalışma Planım:

BTK Akademi: "Sıfırdan İleri Seviye Python Programlama" ve "Algoritma" dersleri takip ediliyor.

Akademik Destek: Ankara Üniversitesi bünyesindeki yönetim ve bilişim sistemleri dersleri ile teknik bilgiler teorik olarak pekiştiriliyor.

Hedef: Kurumsal iş süreçlerini (evrak takibi, randevu sistemleri vb.) dijital algoritmalarla daha verimli hale getirebilecek altyapıyı kurmak.
Ders 1.3: Mantıksal Operatörler ve Karar Mekanizmaları

Algoritmanın temel taşlarından olan mantıksal sorguların ("Ve", "Veya") işleyişini inceledim.

 Kurumsal süreçlerde bir kararın verilmesi için birden fazla şartın (Örn: Hem imza tam hem de tarih uygun mu?) aynı anda kontrol edilmesini otomatiğe bağlamak, hata payını sıfıra indirir.
C# Temel Algoritma ve Kavramlar Notu
Bugün BTK Akademi eğitiminde, ardışık çift sayıların toplamını döngü kullanmadan matematiksel bir formülle hesaplamayı öğrendim.

Kullanılan Anahtar Kelimeler ve Görevleri:

• int: Tam sayı verilerini saklamak için kullanılan hafıza alanı.

• Console.ReadLine(): Kullanıcının klavyeden girdiği veriyi okur (varsayılan olarak metin formatında alır).

• Convert.ToInt32(): Klavyeden gelen metin (string) formatındaki veriyi, üzerinde matematiksel işlem yapılabilecek tam sayı (integer) formatına dönüştürür.

• Console.WriteLine(): İşlem sonucunu ekrana yazdırır.

• n * (n + 1): Ardışık çift sayıların toplamını veren matematiksel formül (Burada n, terim sayısını temsil eder).

Algoritmanın Mantığı:

Döngü kurup sayıları tek tek toplamak yerine, girilen sayıyı ikiye bölerek kaç tane çift sayı olduğunu buluyoruz ve ardından Gauss toplam formülünü uyguluyoruz. Bu yöntem çok daha hızlı ve performanslı çalışır.
1. Algoritma (Yol Haritası)
İlkokul Seviyesinde Anlatım: Bir arkadaşını evine davet ettiğini düşün. Ona "Marketin yanından dön, 3. binaya gir, 2. kata çık" dersin ya, işte bu bir algoritmadır. Adımları karıştırırsan arkadaşın evi bulamaz. Bilgisayara da işleri böyle adım adım tarif ederiz.

E-Ticaret Sitesinde Nasıl Kullanılır? (Örn: Ücretsiz Kargo Kontrolü)

Sepetteki ürünlerin fiyatlarını topla.

Toplam tutar 500 TL'den büyük mü? Kontrol et.

Eğer büyükse: Kargo ücretini 0 TL yap.

Değilse: Kargo ücretini 50 TL olarak ekle.

Sonucu müşteriye göster.

Teknik Not: Bir problemin çözümü için tasarlanan mantıksal, sıralı ve sonlu adımlar bütünüdür.

2. Programlama (Konuşma Dili)
İlkokul Seviyesinde Anlatım: Sen Türkçe konuşuyorsun, bir İngiliz arkadaşın İngilizce konuşuyor. Bilgisayarlar ise sadece elektrikten anlar (açık/kapalı). Onlarla konuşabilmek için "Programlama Dili" denilen ortak dilleri kullanırız. Biz bu dille yazarız, o kendi diline çevirir ve anlar.

E-Ticaret Sitesinde Nasıl Kullanılır?
Sitenizdeki "Satın Al" butonuna basıldığında ne olacağını bu dillerle yazarız. Örneğin; stoktan bir ürün düşülmesi veya müşteriye "Siparişiniz alındı" e-postası gitmesi bu dillerle kodlanır.

Teknik Not: İnsanların isteklerini bilgisayarın anlayabileceği komutlara dönüştürme işlemidir. (Örn: Python, Java, JavaScript).

3. Veri Yapıları (Eşya Düzenleme)
İlkokul Seviyesinde Anlatım: Odandaki oyuncakları düşün. Legoları küçük bir kutuya, büyük topları kocaman bir sepete, kalemleri ise kalemliğe koyarsın. Her şeyi tek bir çuvala atarsan aradığını bulamazsın. Bilgisayar da bilgileri (sayılar, isimler, adresler) türüne göre farklı kutulara koyar ki hızlıca bulabilsin.

E-Ticaret Sitesinde Nasıl Kullanılır? (Örn: Ürün Listesi)
Sitenizde sattığınız 100 farklı ayakkabıyı bir "Liste" (Array/Dizi) içine koyarsınız. Müşteri "en ucuz" dediğinde, bilgisayar o listenin içindeki kutulara tek tek bakıp en küçük sayıyı saniyeler içinde bulur.

Teknik Not: Verilerin bilgisayar belleğinde verimli bir şekilde organize edilmesi ve saklanması yöntemidir.

4. Değişkenler (Etiketli Kavanozlar)
İlkokul Seviyesinde Anlatım: Mutfağınızda kavanozlar olduğunu hayal edin. Birinin üzerine "Şeker", diğerine "Tuz" yazdınız. Kavanozun içindeki şeker bitince yerine yenisini koyabilirsiniz ama kavanozun adı hep "Şeker" kalır.

E-Ticaret Sitesinde Nasıl Kullanılır? (Örn: Sepet Toplamı)
Sepet_Toplami adında bir kavanozumuz var.

Müşteri 100 TL'lik bir gömlek attı -> Kavanozun içine "100" koyduk.

Bir tane daha aldı -> İçindeki sayıyı "200" ile değiştirdik.

Teknik Not: Program çalışırken bilgileri geçici olarak saklamak için kullanılan isimlendirilmiş hafıza alanlarıdır.

GitHub Paylaşımınız İçin Örnek Markdown Notu
Bu kısmı kopyalayıp GitHub'daki "README.md" dosyanıza ekleyebilirsiniz:

Markdown
# Algoritma ve Programlama Temelleri Notlarım 🚀

### 📁 Algoritma
- **Nedir?**: Adım adım çözüm yolu.
- **E-Ticaret Örneği**: İndirim kuponu tanımlama mantığı.
- **Not**: Sıralama çok önemlidir!

### 📦 Veri Yapıları
- **Nedir?**: Bilginin düzenli saklanması.
- **E-Ticaret Örneği**: Kategori listeleri (Elektronik, Giyim vb.).
- **Not**: Doğru veri yapısı hızı artırır.
