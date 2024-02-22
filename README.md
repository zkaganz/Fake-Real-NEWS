# Fake-Real-NEWS
Fake/Real News detection using machine learning
Bu proje, haber başlıklarını ve içeriklerini analiz ederek, haberlerin sahte (fake) veya gerçek (real) olup olmadığını belirlemek için bir makine öğrenimi modeli geliştirir. Model, veri setindeki metin verilerini işleyerek ve özellik çıkararak haberlerin sahte veya gerçek olduğunu tahmin etmek için kullanılır.

 # Veri Seti
Bu proje için veri seti Kaggle platformundan alınmıştır. Veri seti, haber başlıklarını, içeriklerini ve her bir haberin sahte mi gerçek mi olduğunu gösteren etiketleri içerir. Veri seti, sahte ve gerçek haberleri içeren dengeli bir yapıya sahiptir.

# Kullanılan Teknolojiler ve Kütüphaneler
Bu projede aşağıdaki teknolojiler ve kütüphaneler kullanılmıştır:

Python
Pandas
NumPy
Matplotlib
Scikit-learn
NLTK
BeautifulSoup
# Veri İşleme ve Modelleme
Projenin başlangıcında, veri seti Pandas kütüphanesi kullanılarak okunmuş ve gereksiz sütunlar düşürülmüştür. Metin verileri işlenerek, özel karakterler temizlenmiş ve küçük harflere dönüştürülmüştür. Stop-words (durak kelimeler) kullanılarak gereksiz kelimeler kaldırılmış ve metin verileri TF-IDF vektörlerine dönüştürülmüştür.

Modelleme aşamasında, Logistic Regression kullanılarak bir sınıflandırma modeli eğitilmiştir. Ayrıca, veri seti ölçeklendirilerek model performansı artırılmıştır.

# Sonuçlar
Proje sonunda elde edilen model, test veri seti üzerinde %93'ün üzerinde bir doğruluk oranı elde etmiştir. Model, sahte ve gerçek haberleri başarıyla ayırt edebilmektedir.
