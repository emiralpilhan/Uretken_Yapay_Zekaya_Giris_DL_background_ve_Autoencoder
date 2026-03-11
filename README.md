Üretken Yapay Zekaya Giriş: DL Background & Autoencoder
Bu depo, "Üretken Yapay Zekaya Giriş" dersi kapsamında hazırlanan derin öğrenme ve otokodlayıcı (Autoencoder) ödevlerini içermektedir. Projelerde genel olarak NSL-KDD ağ saldırı tespiti (network intrusion detection) veri seti kullanılarak anomali tespiti ve sınıflandırma görevleri gerçekleştirilmiştir.

📂 Depo İçeriği
HW1: CNN, Autoencoder ve AE+CNN Mimarileri
NSL-KDD veri seti üzerinde özellik çıkarımı ve sınıflandırma yapmak üzere TensorFlow/Keras ile geliştirilen modelleri içerir.

Autoencoder (AE): Verinin boyutunu düşürüp temel özelliklerini (latent space) öğrenen model.

CNN: Doğrudan sınıflandırma yapan Evrişimli Sinir Ağı.

AE + CNN (Hibrit): Autoencoder'ın kodlayıcı (encoder) kısmından elde edilen özniteliklerin CNN ile sınıflandırıldığı karma yapı.

Çıktılar: Model dosyaları (.keras), doğruluk (accuracy), kayıp (loss) grafikleri ve karmaşıklık matrisleri (confusion matrix).

HW2: Variational Autoencoder (VAE) ile Anomali Tespiti
PyTorch kullanılarak geliştirilen bu bölümde, anomali tespiti (anomaly detection) için Varyasyonel Otokodlayıcı (VAE) mimarisi kullanılmıştır.

Model normal ağ trafiği üzerinde eğitilmiş ve anormal/saldırı verilerindeki yeniden yapılandırma hatası (reconstruction error) ölçülmüştür.

Çıktılar: Eğitim kayıp grafikleri, eşik değeri karşılaştırmaları (threshold_comparison.csv), ROC eğrileri ve test hata dağılım grafikleri.

📊 Veri Seti
Çalışmalarda siber güvenlik alanında standart bir benchmark olan NSL-KDD (KDDTrain+ ve KDDTest+) veri seti kullanılmıştır.
