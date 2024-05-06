# Machine-Learning-Bootcamp
İlk olarak Kaggle üzerinden Regresyon projesine uygun bi veri seti çektim
veri setim 96453 satırdan ve 12 stündan oluşuyordu
İhtiyaç duyduğum kütüphaneleri ekledikten sonra veri setimi sisteme ekledim 
daha sonra veri setini özetleyip 3 farklı histogram çizdirdim
Veri seti temizliği (eksik değerler içeren satırları silme, gereksiz sütünları kaldırma) ve normalleştirme yaptım.
Veri setini eğitim ve test kümelerine ayırdım %80 eğitim %20 test
Bağımlı ve bağımsız değişkenleri ayırdım bağımsız değişken nem bağımlı sıcaklık görünen sıcaklık. modelleri oluşturdum modelleri eğittim ve test ettim Modellerin K-fold çapraz doğrulama ile R2 değerini Cross-Validation Scoru ve MSE sini hesapladım
Çıkan sonuçlar neticesinde Random Forest Regression modelini daha başarılı gördüm ve Randomized Search yöntemini kullanacağım Parametreleri tanımladım modeli oluşturdum en iyi Hiperparametreleri buldum ve yazdırdım.
Bulduğum en iyi hiperparametreleri aldım en iyi modeli oluşturdum modeli eğittim Tahminleri yaptırdım ve performansını değerlerdirdim
Modelin mse ve mae değerleri : 
Mean Squared Error: 68.17023447975917
Mean Absolute Error: 6.63758059219255
