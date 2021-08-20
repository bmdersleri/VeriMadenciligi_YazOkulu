# Veri Entegrasyonu Nedir?

Veri Entegrasyonu, çeşitli - farklı kaynaklardan ve yazılım formatlarından elde edilen verilerin birleştirilmesi ve kullanıcılara dönüştürülmüş - birleştirilmiş görünümün sunulmasıdır.

Veri entegrasyonunun temelinde verileri daha özgürce erişilebilir kılmak, sistemler ve kullanıcılar tarafından tüketilmesinin, işlenmesinin daha kolay hale getirilmesi vardır.


# Veri Entegrasyonu Nasıl Çalışır?

Verileri bir sistemden diğerine taşımak, verinin yapısını ve anlamını, teknik sistemlerde izleyeceği yolu tanımlayan bir harita veya model gerektirir. Bazen veriler depolanmadan önce gerçekleşir ve bu sürece ETL (çıkarma, dönüştürme, yükleme) adı verilir. Diğer zamanlarda önce verileri depolamak, ardından ELT (çıkarma, yükleme, dönüştürme) olarak bilinen kullanıma hazırlamak daha mantıklıdır.

ETL - Veriler, birden çok kaynak sistemden çıkarılır, kullanılabilir bir biçime dönüştürülür ve ardından kullanıcıların verilerin birleşik görünümü hakkında sorgulama ve raporlama yapabilecekleri bir veri ambarına yüklenir. 

ELT – Veriler, kaynak sistemlerden çıkarılır, bir veritabanı hazırlama alanına yüklenir ve ardından veritabanı içinde kullanılabilir bir formata dönüştürülür. 


# ETL Nedir?

ETL de veri tabanı olarak kullandığımız yerden veriyi extract etmemiz yani veriyi almamız gerekmektedir. Aldığımız veriyi kullandığımız sistemin anlayabilmesi için transform yani çeşitli dönüşüm işlemleri yapmamız gerekir. Ardından elimizde olan veriyi load yaparak sisteme yüklememiz gerekmektedir.

# Veri Entegrasyonu ve ETL Arasındaki Fark

      - Tanım
Veri entegrasyonu, farklı kaynaklarda bulunan verileri birleştirme ve kullanıcılara birleşik bir görüş sunma sürecidir. 
ETL, verileri veri ambarına kaydetmeden önce meydana gelen çıkarma, dönüştürme ve yükleme işlemlerinin üç aşamalı bir işlevidir. 
   
      - Kullanım
Bilimsel ve ticari uygulamalar Veri entegrasyonunu kullanır.
Veri depolama ETL kullanan bir uygulamadır. 
 
      - Sonuç
Veri entegrasyonu ve ETL arasındaki fark, veri entegrasyonunun, kullanıcılara birleşik bir görünüm sağlamak için verileri farklı kaynaklarda birleştirme işlemi iken ETL bir veri ambarı ortamında veri çıkarma, dönüştürme ve yükleme işlemidir.

# ELT Nedir?

Kaynaktan alınan veri hedefe yüklenir ve orada dönüştürür. Burada ETL’den farkı veri hiçbir değişiklik yapılmadan hedefe yüklenir. Yükleme işlemi bittikten sonra veri üzerinde değişiklik yapılır.
Çok büyük veriler ile çalışıyorsak ve kaynak sorunu yaşıyorsak ELT kullanmak daha verimli olacaktır.

# Veri Entegrasyonu Ne İçin Kullanılır

Veri entegrasyonu, yaygın olarak aşağıdakileri yapmak için kullanılır:

      Veri gölü geliştirme: Veri değerini artırmak için verileri silo halindeki şirket içi platformlardan veri göllerine taşır. 
      Veri depolama: Çeşitli kaynaklardan gelen verileri iş amaçlı analiz etmek üzere bir veri ambarında birleştirir. 
      Pazarlama: Müşteri demografisi, sosyal ağ ve web analizi verileri gibi tüm pazarlama verilerinizi analiz ve eylem için tek bir yere taşır.
      IoT (Nesnelerin İnterneti): Birden fazla IoT kaynağından gelen verileri tek bir yerde toplar ve değer elde etmeye yarar.
      Veritabanı çoğaltma: Veri depolamanın en basit ve en tanıdık yolu, hem ilişkisel veri tabanlarını hem de NoSQL veri depolarını içerir ve hiç veri dönüşümü gerektirmeyebilir.

# Veri Entegrasyon Teknikleri

Veri entegrasyonunun gerçekleştirilebileceği birkaç yol vardır. 

    1 ) Manuel Entegrasyon veya Ortak Kullanıcı Ara yüzü
    Kullanıcılar, tüm kaynak sistemlere veya web sayfası ara yüzüne erişerek ilgili tüm bilgilerle çalışır. Verilerin birleşik bir görünümü yoktur. 

      2 ) Uygulama Tabanlı Entegrasyon
      Belirli uygulamaların tüm entegrasyon çabalarını uygulamasını gerektirir. Bu tekniğin dezavantajı, yalnızca çok sınırlı sayıda uygulama olduğunda yönetilebilir olmasıdır.

      3 ) Ara Katman Veri Entegrasyonu
      Entegrasyon mantığını belirli uygulamalardan yeni bir ara katman yazılımı katmanına aktarır. 

      4 ) Ortak Veri Depolama veya Fiziksel Veri Entegrasyonu 
      Orijinal sistemden bağımsız olarak depolamak ve yönetmek için kaynak sistemlerden gelen verilerin bir kopyasını tutan yeni bir sistem oluşturmak anlamına gelir. 

      5 ) Tekdüzen Veri Erişimi veya Sanal Entegrasyon
      Tek tip veri erişimi veya sanal entegrasyon tekniği, verileri kaynak sistemlerde bırakır ve tüm kuruluş genelinde müşterinin birleşik görünümünü sağlamak ve bunlara erişmek       için bir dizi görünüm tanımlar. 

# Veri Entegrasyon Zorlukları

İlk bakışta, en büyük zorluk, farklı ve genellikle uyumsuz kaynaklardan gelen verileri entegre etmenin teknik uygulamasıdır. Ancak, veri entegrasyonunun tamamında çok daha büyük bir zorluk yatmaktadır. Aşağıda veri entegrasyon aşamaları mevcuttur:
 
    Tasarım: Bir şirket içindeki veri entegrasyonu girişimi, bilgi teknolojisi değil, bir iş girişimi olmalıdır. 

    Uygulama: Veri ambarına yeni başlayan küçük şirketler ve işletmeler, çözümü uygulamak için kullanacakları araçlar hakkında bir karara varmalıdır. Daha büyük işletme veya başka veri entegrasyonu projelerine başlamış olan işletmeler, deneyim sahibi olduklarından ve mevcut sistemi genişletebildikleri için daha kolay bir konumdadır. 

     Test yapmak: Uygulamanın dışında, birleştirilmiş verilerin doğru, eksiksiz ve güncel olduğundan emin olmak için uygun testlerin yapılması zorunludur.
             
             Performans Stres testi (PST)
             Teknik Kabul Testi (TAT) 
             Kullanıcı Kabul Testi (UAT)


# Veri Entegrasyon Araçları

Veri entegrasyonu için kullanılan “geleneksel” araçlar gelişmeye devam etmektedir. 
Entegrasyon teknolojileri, Veri Kalitesini ve profil oluşturmayı desteklemek için ortak bir platforma sahip olmalıdır.
Modern şirketler hatta daha küçük olanlar bile günlük işlemlerinde kendilerine yardımcı olacak çok sayıda dijital araç kullanmışlardır. Bunlar, pazarlama ve satış araçlarından lojistik ve işlemsel işleme araçlarına kadar değişebilir.


# Veri Entegrasyon Modelleri

Günümüzde kullanılan çeşitli veri entegrasyon kalıpları vardır. 
1) Veri Çoğaltma = Veri çoğaltma modeli, dünya genelinde kullanılan en eski veri entegrasyon tekniklerinden biridir. Örneğin, iki farklı veri deposu, veri tabanı veya bulut arasındaki veri hareketi sırasında veri çoğaltma gerçekleşebilir. Tüm işlem, verileri harekete geçiren entegratör motorunda önemli değişiklikler yapan bir mekanizma altında gerçekleştirilir.

2) Veri Taşıma = Veri işlemlerinden yararlanan işletmelerde takip edilen önemli veri entegrasyon modellerinden biridir. Veri geçişi, geçiş kapsamının ve veri kümesinin son dönüşümünün işlemden önce belirlendiği düzenli bir süreçtir. Sonunda, bu sürecin sonuçları, sürecin uygunluğunu sağlamak için istenen sonuçlarla karşılaştırılır. Bu veri entegrasyon işlemi aynı anda birkaç büyük veri hacmini işlemek için tasarlanmıştır.

3) Veri Sanallaştırma=Ticari veri entegrasyonunun hızla gelişen modellerinden biridir. Farklı veri tabanlarından gelen verileri tek bir fiziksel veri tabanında birleştirmeyi sağlar veya verilerin diğer kullanımlar için verimli bir şekilde kullanılmasını sağlayan tüm yollarla yeniden oluşturulmasına izin verir. 

4) Yayın, İki Yönlü Senkronizasyon ve Korelasyon= Bu işlemler, farklı sistemler arasında veri güncellemek için bir ihtiyaç olduğunda kullanılır.
      
       Yayıncılık: Bu işlemde, bir sistemde depolanan veriler gerçek zamanlı olarak birçok hedef veri deposuna taşınır. Yayıncılık aynı zamanda “tek yönlü senkronizasyon” olarak da bilinir, çünkü veri hareketi kaynak sistemden hedef sisteme tek yönlüdür. 

       İki Yönlü Senkronizasyon: Bu süreçte, iki ayrı sistemden iki veri deposu tek bir sistem gibi davranmak için birleştirilir. Bu senkronizasyon ayrıca farklı veri depoları olarak var olma önceliğini de dikkate alır.

       Korelasyon: İki veri setinin kesişme noktasında iki yönlü senkronizasyonun yapıldığı bir işlemdir.

Toplama: Bu işlemde, birden çok sistemden gelen veriler tek bir birleşik sistemde toplanır. Bu veri entegrasyon tekniği, işletmelerin verileri güncel tutmasına yardımcı olur ve istenen veri setini üretmek için verileri işlemelerine veya birleştirmelerine izin verir.
Sonuç: Bahsettiğimiz bu veri entegrasyon tekniklerinin tümü, işletmelere çeşitli dijital kaynaklar tarafından üretilen büyük miktarda veriyi ele almada yardımcı olan esneklik ve çeviklik sunar. Bu teknikler sadece organizasyon genelinde düzenli bir veri alışverişi sağlamakla kalmaz, aynı zamanda sağlam bir işletmeler arası entegrasyon veri bağlantısı kurmanıza yardımcı olur.


# SONUÇ

Büyük Veri Entegrasyonunu görmezden gelmek, uzun vadede, verimsizlik ve zaman kaybına sebep olur. Birçok kurumsal lider, gerekli değerlendirmeleri ve testleri yapmadan, tüm veri entegrasyonu çözümlerinin eşit olduğuna inandığı teknolojiyi kabul eder. Aslında, fonksiyonlar ve ele alınan problemler açısından, çeşitli veri entegrasyonu teknolojileri bulunmaktadır. Dikkate alınacak hususlar performansı, Veri Yönetimini ve güvenliği içermelidir.
Veri entegrasyonu farklı kaynaklardan elde edilen işlenmiş veya işlenmemiş verileri yorumlama, görselleştirme ve raporlama gibi amaçlarla yapılan veriyi bütünleştirme işlemidir. 
Veritabanındaki ham verinin bilgiye, bilginin tecrübeye, tecrübenin verime dönüşmesiyle kar oranını artırabilir ve işinizi büyütebilirsiniz. Veri entegrasyonu, şirketiniz içinde geleceğe dönük olumlu veya olumsuz tahminler yapar, muhtemel hatanın gelecekteki konumunu ve zamanını öngörür, azalan verimin istatistiksel sebeplerini analiz eder.
Veri entegrasyonuna yatırım yapan şirketler çoğunlukla rekabet ettiği sektörde öncüdür.

# 

   Youtube Kanalımız: BMDersleri

   Bağlantı: https://www.youtube.com/bmdersleri

   Konu ile ilgili Youtube Video Linki : https://youtu.be/TacvMPS32Go

   Kısa Bağlantı: https://bit.ly/32k9MnJ

   Github Adresimiz: https://github.com/bmdersleri

   Hazırlayan: Seda Nur POLATER



