# Knime Programının Kullanımı

# Hakımızda

Youtube Kanalımız: BMDersleri

Bağlantı: https://www.youtube.com/channel/UCIdYgV-XFjv9q0IHtzUTtQw

Konu ile ilgili Youtube Video Linki : https://youtu.be/S5ayqpTvEkw

Kısa Bağlantı: https://bit.ly/32k9MnJ

Github Adresimiz: https://github.com/bmdersleri

Hazırlayan: Ahmet Çetinkaya - https://ahmetcetinkaya.info



## Giriş
Bu sunum, Knime programının kullamını göstermeye yöneliktir. Sunum ile birlikte Knime nedir, Knime kurulum adımları, knime nasıl kullanılır, knime düğüm (node) nedir, knime yapılandırma (configure), knime eklentiler (extension) konularını öğrenecek ve knime örnek ile pekiştireceksiniz. Ayrıca ilgili örneği indirebilir kendiniz denemeler yapabilirsiniz.

## Knime Nedir?
- KNIME açık kaynak ve çapraz platform veri analizi, raporlama, entegrasyon platformudur. 

- KNIME, modüler veri hattı konsepti aracılığıyla makine öğrenimi ve veri madenciliği için çeşitli düğümler (node) içerir.

- Görselleştirme, modelleme ve veri analizi için temel veri önişleme düğümlerini, bir kullanıcı grafik arabiriminde sürükle bırak yöntemiyle, herhangi bir kod yazmadan kullanılmasını sağlar.

- Böylelikle knime daha kolay ve daha kısa süren veri bilimi çalışması yapılabilmesine olanak tanır.

- KNIME 2006 yılından beri ilaç araştırmalarında, CRM analizlerinde, iş zekası ve finansal uygulamalarda kullanılmaktadır.

## Knime Kurulum
- www.knime.com adresine girin.

- İndirme işlemini tamamlayın:

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129485699-c817ac94-7132-44a7-8ec3-68ded098a633.mp4"></video>

- Kurulum işlemlerini tamamlayın:

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129485811-e156ebc8-dcd2-40b5-bd98-804525df2a3d.mp4"></video>

## Knime Tanıtım

- Knime programını başlattığımızda bizi aşağıdaki gibi bir pencere karşılıyor.

![Resim1](https://user-images.githubusercontent.com/53148314/129485878-dc6fddfc-4a5e-4507-9933-85bbf965d7dd.png)


- KNIME Explorer (Gezgin): Local (yerel) sekmesinde mevcut iş akışlarına (workflow) erişebilir ve yönetebilirsiniz. Aynı zamanda sunucu bağlantılarını da buradan erişebilir ve yönetebilirsiniz. Examples (örnekler) sekmesinde büyük veri (big data), veri erişimi (data access), veri işleme (data manipulation), analitik (analytics), raporlama (reporting) gibi birçok örnek iş akışlarına ulaşılabilir.

![Resim2](https://user-images.githubusercontent.com/53148314/129485901-3db87e68-5744-4ffe-9c20-bc0130b98fb6.png)

- Workflow Coach (İş akışı koçu): Bir iş akışı (workflow) üzerinde çalışırken, iş akışınıza eklenebilecek düğüm (node) tavsiyelerinde bulunur. Örneğin, bir iş akışı başlatmak için düğümler önerebilir veya bir düğüme tıkladığınızda düğümü takip eden popüler düğümleri de gösterebilir.

![Resim3](https://user-images.githubusercontent.com/53148314/129485910-eca017fa-fcd6-4bba-93fc-f561b54ce204.png)

- Node Repository (Düğüm Deposu): İş akışlarında kullanılabilecek tüm düğümleri içerir. En çok kullanılan kısımlardan biridir. Düğümlerin işlevlerine göre sınıflandırıldığını görebiliriz. Örneğin IO (Input Output (Giriş Çıkış)) başlığının altında dosya okuma ve yazma düğümlerine veya Analytics (Analitik) başlığının altında veri kazımı veya istatistik düğümlerine ulaşılabilir.

![Resim4](https://user-images.githubusercontent.com/53148314/129485924-e914f9a2-e292-4366-94ab-3e4a6d2ae733.png)

- Workflow (iş akışı): Bu bölüm düğümleri (node) sürükleyip bıraktığımız, işlevlerini ve ilişkilerini tanımladığımız, tasarladığımız çalışma alanıdır.

![Resim5](https://user-images.githubusercontent.com/53148314/129485939-cf324f2a-d308-4cda-b425-81b450a8f97f.png)

- Outline (anahat): İş akışının (workflow) uzaktan haritasını gösterir.

![Resim6](https://user-images.githubusercontent.com/53148314/129485950-c4dbaecd-41f1-4265-9d1a-9de232c0426f.png)

- Description (Açıklama): İş akışında (workflow) seçilen bir düğümün (node) açıklamasını gösterir. 

![Resim7](https://user-images.githubusercontent.com/53148314/129485991-413502fe-cd91-4841-81c6-b83cfdf78309.png)

- Console (Konsol): Console sekmesi iş akışının yürütülmesindeki uyarı ve hata mesajlarını içerir.

![Resim8](https://user-images.githubusercontent.com/53148314/129486007-b5a18660-a857-45e9-b40b-dd292a728403.png)

- Node Monitor (Düğüm Monitörü): İş akışındaki düğümlerin (node) ara çıktı tablolarını gösteren kısımdır.

![Resim9](https://user-images.githubusercontent.com/53148314/129486015-ada3fc3e-cc8a-4f0e-a210-2d4da2f1a456.png)

## Knime Çalışma Yapısı
- KNIME kullanıcıların görsel olarak veri akışları oluşturmalarını, çeşitli analiz adımlarının gerçekleştirilmesini, daha sonra modelleri, sonuçları ve etkileşimli görünümlerin incelenmesini sağlar. Veri işleme sürecinde, görselleştirmede ve modellemede kısacası veri analizi için kullanılan her bir işlemi temsil eden düğümler (node) bulunmaktadır. Bu düğümler iş akışı (workflow) bölümüne sürükle bırak yaparak yerleştirilebilir ve diğer düğümlerle olan ilişkileri tasarlanabilir.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486028-dfcb9819-c7da-48be-aee7-0e8d07b33861.mp4"></video>
<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486030-9592485a-364b-4472-a310-034d2d82bc62.mp4"></video>

## Düğümlerin (node) Anlamları
- Her düğüm için girdi ve çıktılardan oluşur. Böylece diğer düğümlerle veri aktarımı sağlanır. Örneğin; File Reader (dosya okuyucu), genelde ilk adım olduğu için, sadece çıkış (output) bölümü vardır. Partitioning (bölme) düğümü ise girdi (input) ve çıktı (output) bölümüne sahiptir.

![Resim10](https://user-images.githubusercontent.com/53148314/129486068-5a861bc7-2cc5-4752-8a20-81db5afd9ff8.png)

- Her düğümün altında trafik ışıklarına benzer durum göstergesi bulunmaktadır. Kırmızı, sarı, yeşil ve hata olmak üzere 4 farklı gösterge biçimi vardır. Bu göstergelerin her birinin anlamı bulunmaktadır:

- ![Resim11](https://user-images.githubusercontent.com/53148314/129486122-e4e38367-1094-486e-97b7-e2dbc7a78275.png) Gerekli ayarlamaların henüz yapılmadığını gösterir.
- ![Resim12](https://user-images.githubusercontent.com/53148314/129486121-2ab59b0c-b35c-46cf-a851-10c7bf5e4e36.png) Henüz çalıştırılmadığını gösterir.
- ![Resim13](https://user-images.githubusercontent.com/53148314/129486120-2f7c45c4-5ee1-434a-ba7e-0228fb5de154.png) Çalışma sırasında bir hata oluştuğunu gösterir.
- ![Resim14](https://user-images.githubusercontent.com/53148314/129486118-c660a3d6-2a4c-4b7c-92be-0c4e97e838b4.png) Başarılı bir şekilde çalıştığını gösterir.

- Bazı düğümlerin girdi ve çıktıları farklı biçimlerde olabilir. Bunları belirten farklı renklerde ve biçimlerde göstergeler bulunmaktadır.

![Resim15](https://user-images.githubusercontent.com/53148314/129486181-e92933d8-d948-4cef-bdf7-1a6809106caf.png)

## Yapılandırma  İşlemi
- Düğümü çalıştırmadan önce gerekli ayarlamaları yapmamız gerekiyor. Bunu için düğüme çift tıklayarak veya sağ tıkladığımızda açılan pencerede Configure (yapılandırma) seçeneğine tıklayarak ayarlar menüsüne ulaşabiliriz. Düğüme ait ayarları görebilir ve düzenleyebiliriz.

![Resim16](https://user-images.githubusercontent.com/53148314/129486199-5d8fcfd9-9735-4ede-8471-ef89da3cfb87.png)
![Resim17](https://user-images.githubusercontent.com/53148314/129486198-89be4926-d4b3-43a5-b69e-9f4b0de7d62e.png)

## Eklentiler
- KNIME en temel hali ile veri entegrasyonu, veri dönüşümü, veri analizi ve görselleştirme için yaygın yöntemleri kullanan yüzlerce modül içermektedir. Temel özelliklere ek olarak, R dili, Weka, Tableau gibi uygulamalar başta olmak üzere ihtiyaç duyabileceğiniz bir çok geliştirme ve özelleştirme paketlerini eklentiler yardımıyla eklenebilir.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486210-97e33046-64d9-4022-993b-8393c13c341b.mp4"></video>

## Uygulama Örneği 
- Uygulama örneğimizi Iris veri seti üzerinden Decision Tree (karar ağacı) algoritmasını kullanarak gerçekleştireceğiz.
İlk olarak yeni bir knime iş akışı oluşturmamız gerekiyor.

- İlk olarak yeni bir knime iş akışı oluşturmamız gerekiyor.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486306-3392d780-3d83-41d8-b69c-ea359381a2b2.mp4"></video>

- https://www.kaggle.com/uciml/iris adresinden Iris veri setimizi indirelim.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486343-4295284b-453d-4755-b69f-8642565c6c1c.mp4"></video>


- İndirdiğimiz Iris.csv dosyasını okuyabilmek adına CSV Reader (okuyucu) düğümünü kullanabiliriz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486356-94559af8-8e9e-4f33-b93e-818c58f8a44c.mp4"></video>

- CSV Reader (okuyucu) düğümü ayarlarından indirdiğimiz Iris veri setini seçerek düğümü yapılandırıyoruz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486377-50689499-6b51-49e0-abf3-13ccce728768.mp4"></video>

- Düğümü çalıştırabilir ve hangi verileri okuduğuna göz atabiliriz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486397-ac7cb434-5f6d-4e34-b3bf-1fdcececcc72.mp4"></video>

-  Kullandığımız Irıs veri setinin istatistiksel bilgilerini görmek için Statistics (istatistik) düğümünü kullanabiliriz. CSV Reader’dan aldığımız veri çıkışını, girdi olarak Statictics düğüme eklemeliyiz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486409-d0744d50-efbe-420f-a99f-bc278cd7d4d4.mp4"></video>

- Statictics (istatistik) düğümü ayarlarından gözlemlemek istediğimiz sütunları include (dahil etmek) kısmından, istemediğimiz sütunları ise exclude (hariç tutmak) kısmından belirtebiliriz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486419-2127cece-49a5-4a11-a0e1-da1dc5c16e42.mp4"></video>

- Statictics (istatistik) düğümünü çalıştırdığımızda, statistics view (istatistik görünümü) seçeneğinden sonuçları görebiliriz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486429-b559e5c8-1e5d-4e15-a6a7-8fc8babd6e45.mp4"></video>

- Scatter Plot (dağılım grafiği) düğümü, seçilen iki kolonun dağılım grafiğini çizebilir. Aynı şekilde CSV Reader (Okuyucu)’dan aldığımız çıktıyı girdi olarak almalıyız.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486438-8e76e632-16cb-44a8-a05d-763612b4dc2b.mp4"></video>

- Scatter Plot (dağılım grafiği) düğümü çalıştırdıktan sonra scatter plot (dağılım grafiği) seçeneğine tıklayarak sonuçlara bakabiliriz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486445-05f5daf4-cc57-41b2-97fb-af103286a331.mp4"></video>

- Partitioning (bölme) düğümü ile veri setini eğitim ve test olarak bölme işlemini gerçekleştirebiliriz. Aynı şekilde CSV Reader düğümünün çıktısını girdi olarak almamız gerekmekte.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486453-a9a3a18e-096e-480e-99ad-da6995c80a30.mp4"></video>

- Partitioning (bölümleme) düğümünü çalıştırmadan önce hangi oranda bölümleme yapacağımızı ayarlardan belirtmemiz gerekiyor. Relative (oransal) seçeneği ile yüzde üzerinden verilerin %66’sını eğitim için, kalan %34’ünü ise test için bölümleyebiliriz. 
- Ek olarak Stratified sampling (Katmanlı örnekleme) seçeneği ile de bölümleme işleminde veri setindeki tür etiketlerinin yüzdelik oranlarının korunmasını belirtebiliriz. Örneğin veri setimizin %20’sini “setosa”, %55’ını “versicolor”, kalan %25’ini ise “virginica” türleri oluşturuyor. Eğitim ve test verimizde de bu oranlar korunacaktır.
- Yapılandırmadan sonra düğümü çalıştırabiliriz. Bölümleme işlemi sonucunda 2 adet veri seti olacağı için 2 adet çıkış bulunmakta. Üstteki çıkış eğitim veri setimizi, alttaki çıkış test veri setimizi çıktı olarak vermektedir.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486468-7ee94f80-4b3d-48e8-adfc-3f5ceb69133c.mp4"></video>

- Decision Tree Learner (Karar Ağacı Öğrenicisi) düğümü ile veri setinden bölümlediğimiz eğitim veri setine göre karar ağacı oluşturabiliriz.  Girdi olarak partitioning (bölümleme) düğümün eğitim veri seti için ayrılan üstteki çıkışı kullanmalıyız.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486532-83494784-6797-4b66-a910-b7457f0c6db3.mp4"></video>

- Ayarlarında ise class column (sınıf sütun) kısmından tahmin edilecek sütunu yani tür sütununu belirtiyoruz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486541-deef31b9-8c73-494b-92d2-ff2e56b568bb.mp4"></video>

- Artık düğümü çalıştırabiliriz. Çıkış olarak bize bir model verisi verdiğini görebiliriz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486556-f7957a6e-e5a8-4c07-9a50-fb9990bde53b.mp4"></video>

- Decision Tree Predictor (Karar Ağacı Tahmincisi) düğümü ile oluşturulan kurallar doğrultusunda test veri setinde tahmin işlemlerini gerçekleştirir. Model girişine Decision Tree Learner (Karar Ağacı Öğrenicisi)’ın çıkışı olan modeli, veri girişine ise test veri setimizi bağlıyoruz. Girişleri ayarladıktan sonra düğümü çalıştırabiliriz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486561-0f95221d-25c6-44d0-9598-530fffe50de3.mp4"></video>

- Son olarak modelin başarısını test etmek için Scorer (Puanlayıcı) düğümünü kullanacağız. Giriş olarak Decision Tree Learner (Karar Ağacı Öğrenicisi)’in çıkış verisini kullanacağız.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486573-e1a582c0-9582-46b6-9f9c-d9e475cb3aa1.mp4"></video>

- Ayarlarında ise  (ilk sütun) seçeneği tahmin edilen sütunu, Second column (ikinci sütun) ise algoritmanın tahmin ettiği değerleri belirtiyoruz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486579-8d1d9c87-c2cd-4a22-9c64-86bea0bf909f.mp4"></video>

- Örneğimizin son adımı olarak Scorer (puanlayıcı) düğümünü çalıştırıp, confusion matrix (karışıklık matrisi) seçeneğinden sonuçlara ulaşabiliriz.

<video controls="true" allowfullscreen="true" src="https://user-images.githubusercontent.com/53148314/129486596-56844d8f-4000-40be-a0fe-a0043de1ebb1.mp4"></video>

## Sonuç
- KNIME, veri analizi, raporlama, entegrasyon platformudur.

- KNIME kullanıcıların görsel olarak veri akışları oluşturmalarını, çeşitli analiz adımlarının gerçekleştirilmesini, daha sonra modelleri, sonuçları ve etkileşimli görünümlerin incelenmesini sağlar. 

- KNIME, modüler veri hattı konsepti aracılığıyla makine öğrenimi ve veri madenciliği için çeşitli düğümler (node) içerir.

- Düğümler (node) iş akışı (workflow) bölümüne sürükle bırak yaparak yerleştirilebilir ve diğer düğümlerle bağlantıları sağlanarak bir iş akışı kolayca oluşturulabilir.

## Kaynaklar
- [KNIME - Vikipedi](https://tr.wikipedia.org/wiki/KNIME)
- [KNIME ile Uçtan Uca Veri Bilimi](https://sadievrenseker.com/wp-content/uploads/veribilimi_knime.pdf)
- [KNIME Nedir?](https://ceaksan.com/tr/knime-nedir)
- [KNIME ile Veri Bilimi](https://www.datasciencearth.com/knime-ile-veri-bilimi/)
- [KNIME ile Veri Analizi](https://medium.com/datarunner/knime-ile-veri-analizi-51add5411831)

