Bahşiş Tahmin Modeli 

Bu proje, bir restoranda müşterilerin hesap tutarına göre verdikleri bahşiş miktarını tahmin eden doğrusal regresyon modeli içermektedir. Seaborn "tips" veri seti kullanılarak, müşteri hesap tutarları ve verdikleri bahşişler arasında bir ilişki kurulmuştur. Model, Scikit-Learn kütüphanesi kullanılarak eğitilmiş ve test edilmiştir. 

Kullanılan Teknolojiler 
- Python 
- NumPy, Pandas 
- Scikit-Learn (Linear Regression, Train-Test Split, MSE) 
- Seaborn, Matplotlib 

Proje Açıklaması 
1. Veri seti Seaborn üzerinden yüklenir. 
2. Gerekli öznitelikler seçilir ve kullanılmayacak sütunlar kaldırılır. 
3. Bağımsız değişken (total_bill) ve bağımlı değişken (tip) vektör haline getirilerek modele uygun hale getirilir. 
4. Veri eğitim ve test kümelerine bölünerek doğrusal regresyon modeli eğitilir. 
5. Modelin başarısı Mean Squared Error (MSE) metriği ile değerlendirilir.
6. 26.5 TL hesap ödeyen bir kadının tahmini bahşiş miktarı ayrıca hesaplanarak analiz edilmiştir. 
7. Sonuçlar **matplotlib ile grafik olarak görselleştirilmiştir.


