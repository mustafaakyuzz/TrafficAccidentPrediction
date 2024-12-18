# Traffic Accident Prediction

This project is a Python application that uses data analysis and machine learning techniques to predict the likelihood of traffic accidents.

## Steps

- Analysis and visualization of traffic accident data  
- Comparison of different machine learning algorithms  
- Training the best identified model to predict the likelihood of traffic accidents  
- Evaluation of prediction results and accuracy analysis  

## About the Dataset

**Traffic Accident Prediction Dataset**  
This dataset is designed to predict the likelihood of traffic accidents based on various factors. It includes variables related to road conditions, driver behavior, and traffic situations.

### Features

1. **Weather**: The impact of weather conditions on traffic accidents.
   - Clear: No adverse weather conditions.
   - Rainy: Rainy conditions.
   - Foggy: Foggy conditions.
   - Snowy: Snowy conditions.
   - Stormy: Stormy weather.

2. **Road_Type**: The type of road, affecting the probability of accidents.
   - Highway: High-speed roads.
   - City Road: Roads within city limits.
   - Rural Road: Roads outside urban areas.
   - Mountain Road: Roads with curves and elevation changes.

3. **Time_of_Day**: The time of day when the accident occurs.
   - Morning: From sunrise to noon.
   - Afternoon: From noon to evening.
   - Evening: Before sunset.
   - Night: Nighttime with reduced visibility and higher risk.

4. **Traffic_Density**: The level of traffic on the road.
   - 0: Low density.
   - 1: Moderate density.
   - 2: High density.

5. **Speed_Limit**: The maximum allowed speed on the road.

6. **Number_of_Vehicles**: The number of vehicles involved in the accident (range: 1-5).

7. **Driver_Alcohol**: Whether the driver consumed alcohol.
   - 0: No alcohol consumption.
   - 1: Alcohol consumption.

8. **Accident_Severity**: The severity of the accident.
   - Low: Minor accident.
   - Moderate: Moderate accident.
   - High: Severe accident.

9. **Road_Condition**: The condition of the road surface.
   - Dry: Dry roads.
   - Wet: Wet roads.
   - Icy: Icy roads.
   - Under Construction: Roads under construction.

10. **Vehicle_Type**: The type of vehicle involved in the accident.
    - Car: Passenger cars.
    - Truck: Trucks.
    - Motorcycle: Motorcycles.
    - Bus: Buses.

11. **Driver_Age**: The age of the driver (range: 18-70 years).

12. **Driver_Experience**: The driver’s experience in years (range: 0-50 years).

13. **Road_Light_Condition**: Lighting conditions on the road.
    - Daylight: During daytime.
    - Artificial Light: Roads illuminated with streetlights.
    - No Light: Unlit roads, typically during the night.

---

# Trafik Kazası Tahmini

Bu proje, trafik kazalarının meydana gelme olasılığını tahmin etmek için veri analizi ve makine öğrenimi tekniklerini kullanan bir Python uygulamasıdır.

## Adımlar

- Trafik kazası verilerinin analizi ve görselleştirilmesi  
- Farklı makine öğrenimi algoritmalarının karşılaştırılması  
- Trafik kazalarının olasılığını tahmin etmek için tespit edilen en iyi modelin eğitilmesi  
- Tahmin sonuçlarının değerlendirilmesi ve doğruluk analizi  

## Veriseti Hakkında

**Traffic Accident Prediction Dataset**  
Trafik kazalarının meydana gelme olasılığını tahmin etmek için çeşitli faktörlere dayalı olarak oluşturulmuş bir veri kümesidir. Bu veri kümesi, yol koşulları, sürücü davranışı ve trafik durumları gibi değişkenleri içerir.

### Özellikler

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
