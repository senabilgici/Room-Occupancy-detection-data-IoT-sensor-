# Room-Occupancy-detection-data-IoT-sensor-

İzlenecek adım: Gerçek IoT verisi üzerinde gözetimli öğrenme algoritmalarını test edilecek. Amaç, verideki değişkenleri analiz ederek odada insan varlığını (occupancy) tespit etmek.
Üç adet veri seti mevcut: 
1)	Veriseti1: Kapılar kapalıyken alınmış ölçümler. 
2)	Veriseti2: Kapılar kapalıyken alınmış başka bir veri seti. Veriseti3: Kapılar açıkken alınmış ölçümler.
3)	Hedef parametre: Occupancy. İnsan varlığı 1, insan yokluğu 0 değerlerine karşılık geliyor.

Kavramlar:

CO2 = Oksijen 										                        
Humidity = Nem										   
HumidityRatio = Nem Oranı 								                                  
Light = Işık 									                                                                
Occupancy = İnsan varlığı                                                                                                                                      
Temperature = Sıcaklık

_Verilen verisetlerin içerisine yeni bir Nem+Nem Oranı kavramı daha sonradan eklenmiştir. Daha sonra bu kavramlar farklı görselleştirme metotları kullanılarak matris ve grafikler gösterilmiştir. Son olarak Random Forest, Support Vector Machine, Logistic Regression, KNN, Decision Tree ve Naive Bayes sınıflandırıcıları birbirleri ile Accuracy_score'larına göre karşılaştırılıp yüksekten düşüğe göre grafiksel olarak gösterilmiştir._

**Python dili ile yazılmıştır.**

