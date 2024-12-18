# Traffic Accident Prediction

Bu proje, trafik kazalarının meydana gelme olasılığını tahmin etmek için veri analizi ve makine öğrenimi tekniklerini kullanan bir Python uygulamasıdır.

## Özellikler

- Trafik kazası verilerinin analizi ve görselleştirilmesi  
- Farklı makine öğrenimi algoritmalarının karşılaştırılması  
- Trafik kazalarının olasılığını tahmin etmek için tespit edilen en iyi modelin eğitilmesi  
- Tahmin sonuçlarının değerlendirilmesi ve doğruluk analizi  

## Veri Kümesi Hakkında

**Traffic Accident Prediction Dataset**  
Trafik kazalarının meydana gelme olasılığını tahmin etmek için çeşitli faktörlere dayalı olarak oluşturulmuş bir veri kümesidir. Bu veri kümesi, yol koşulları, sürücü davranışı ve trafik durumları gibi değişkenleri içerir.

### Özellikler

```plaintext
1. Weather (Hava Durumu): Havanın trafik kazalarına etkisi.
   - Clear: Açık hava.
   - Rainy: Yağmurlu.
   - Foggy: Sisli.
   - Snowy: Karlı.
   - Stormy: Fırtınalı.

2. Road_Type (Yol Türü): Yolun türü, kazaların meydana gelme ihtimalini etkiler.
   - Highway: Yüksek hız limitine sahip yollar.
   - City Road: Şehir içi yollar.
   - Rural Road: Şehir dışındaki yollar.
   - Mountain Road: Virajlı ve eğimli yollar.

3. Time_of_Day (Günün Saati): Kazanın gerçekleştiği saat dilimi.
   - Morning: Sabah (gün doğumundan öğlene kadar).
   - Afternoon: Öğleden sonra (öğlen ile akşam arası).
   - Evening: Akşamüstü (gün batımından önce).
   - Night: Gece (düşük görüş alanı ve daha yüksek risk).

4. Traffic_Density (Trafik Yoğunluğu): Yoldaki araç yoğunluğu.
   - 0: Düşük yoğunluk.
   - 1: Orta yoğunluk.
   - 2: Yüksek yoğunluk.

5. Speed_Limit (Hız Limiti): Yoldaki maksimum hız sınırı.

6. Number_of_Vehicles (Araç Sayısı): Kazaya karışan araç sayısı (1-5 arasında).

7. Driver_Alcohol (Sürücü Alkol Durumu): Sürücünün alkol tüketimi durumu.
   - 0: Alkol tüketimi yok.
   - 1: Alkol tüketimi var.

8. Accident_Severity (Kaza Şiddeti): Kaza şiddeti.
   - Low: Hafif kaza.
   - Moderate: Orta şiddette kaza.
   - High: Ağır kaza.

9. Road_Condition (Yol Durumu): Yol yüzeyi koşulları.
   - Dry: Kuru yol.
   - Wet: Islak yol.
   - Icy: Buzlu yol.
   - Under Construction: Yol yapım aşamasında.

10. Vehicle_Type (Araç Türü): Kazaya karışan aracın türü.
    - Car: Binek araç.
    - Truck: Kamyon.
    - Motorcycle: Motosiklet.
    - Bus: Otobüs.

11. Driver_Age (Sürücü Yaşı): Sürücünün yaşı (18-70 arasında).

12. Driver_Experience (Sürücü Deneyimi): Sürücünün tecrübesi (0-50 yıl).

13. Road_Light_Condition (Yol Aydınlatma Durumu): Yolun aydınlatma durumu.
    - Daylight: Gün ışığı.
    - Artificial Light: Sokak lambalarıyla aydınlatılmış yol.
    - No Light: Aydınlatma olmayan karanlık yol.
