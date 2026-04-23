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
