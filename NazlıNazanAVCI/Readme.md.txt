# Sınıflandırma Algoritmaları #
Sınıflandırma: İki temel sınıflandırma türü vardır: İkili ve çok sınıflı problem. 
## Naive Bayes ##
##### Naive Bayes sınıflandırıcısı muhtemelen bugün endüstride 
en temel ve yaygın olarak kullanılan yöntemlerdir. Basittir, hızlıdır,
 kolayca güncellenir ve birçok teorik ve hatta teknik tuzaklara rağmen pratikte oldukça etkilidir. 
Bayes teoreminden faydalanılarak oluşturulan bir algoritmadır. #####
## K-En Yakın Komşu ## 
##### Komşu tabanlı sınıflandırma, 
bir örnek tabanlı öğrenme veya genelleştirmeyen öğrenme türüdür:
 Genel bir dahili model oluşturmaya çalışmaz, yalnızca eğitim verilerinin örneklerini depolar.  #####

## Karar Ağaçları ## 
##### Karar Ağacı Öğrenme Modeli, klasik ve doğal bir öğrenme modelidir. 
Temel bilgisayar bilimi kavramı olan “böl ve yönet” kavramıyla yakından ilişkilidir. 
Karar ağaçları birçok öğrenme problemine uygulanabilse de, en basit durumla başlanır: ikili sınıflandırma. #####

### Rasgele Orman ### 
##### Rasgele Orman farklı ön yüklenmiş örnekler ve alt örneklenmiş
 özellikler üzerine kurulmuş çok sayıda karar ağacı modeli 
kullanan bir sınıflandırma (doğal olarak çok sınıflı) ve regresyon algoritmasıdır.
 Algoritma kullanımı kolay ve anlaşılırdır. 
(temeli karar ağacıdır)  Basitliği nedeniyle 
RO, herkesin makine öğrenimini başarıyla uygulamasına izin verebilir.
 Bir ölçü (entropi veya gini indeksi) optimize ederek ağaçlar oluşturulabilir;
 Ağaç tamamlandığında ölçüyü en çok geliştiren özelliği seçer. Algoritma birkaç tekrarlanan adımla çalışır #####

### Lojistik Regresyon ###
##### Lojistik regresyon sadece sınıflar arasındaki sınırın nerede olduğunu 
söylemekle kalmaz, aynı zamanda sınıf olasılıklarının 
belirli bir şekilde sınırdan uzaklığa bağlı olduğunu ve 
bunların uç noktalara (0 ve 1) doğru gittiğini söyler. Lojistik regresyonu bir 
sınıflandırıcıdan daha fazlası yapan, olasılıklarla ilgili ifadelerdir.  #####

### Destek Vektör Makineleri ### 
##### Yüksek boyutta doğrusal sınıflandırma yapabilir. 
Bir düzlemde bulunan iki grubu ayırmak için bu iki grup üyelerine en uzak çizilen sınırın nasıl 
çizileceğini belirler. Sınıfları ayırmak için en büyük uzaklığı olan doğrusal fonksiyonu arar. 
Doğrusal olarak ayrılamıyorsa daha yüksek boyutlu üst uzaya taşıyarak sınıflandırma yapar. #####

### Karışıklık Matrisi ### 
##### Yanlış tahminler yapan modelin sebep olduğu karışıklığı özetlemeye yardımcı olur. 
Kısacası, karışıklık matrisi, bir sınıflandırma algoritmasının performansını özetlemek 
için kullanılan bir tekniktir, yani ikili çıktılara sahiptir. Bir karışıklık matrisi, 
sınıflandırma modelimizin neyi doğru tahmin ettiği ve ne tür hatalar yaptığı konusunda 
bize daha iyi bir fikir verir #####

### F1 puanı ### 
##### F1 puanı, kesinlik ve geri çağırmanın harmonik ortalamasıdır.
F1-puanının mümkün olan en yüksek değeri 1.0'dır,  bu da mükemmel kesinliği ve geri çağırmayı gösterir 
ve kesinlik veya geri çağırma sıfır ise mümkün olan en düşük değer 0'dır.  #####

