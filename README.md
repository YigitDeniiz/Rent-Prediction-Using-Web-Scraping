# Rent-Prediction-Using-Web-Scraping

Proje Adı: "Istanbul Kağıthane Emlak Fiyat Tahmini"

Amaç: Bu proje, Hepsi Emlak sitesinden İstanbul Kağıthane bölgesindeki evlerin verilerini çekerek fiyat tahmini yapmak için Selenium kullanılarak web scraping yapmayı ve ardından bu verileri işleyerek uygun bir modelle eğitmeyi amaçlamaktadır.

Kullanılan Program ve kitaplıklar:
Python
Jupyter Notebook
Selenium (Web scraping için)
Veri işleme ve model eğitimi için uygun kütüphaneler (örneğin: Pandas, sklearn, seaborn vb.)

Proje İçeriği:
Web_Scraping_Selenium.ipynb: Selenium kullanarak Hepsi Emlak sitesinden veri çekme işlemlerini içerir.
Price Prediction Model.ipynb: Çekilen verilerin işlenmesi ve uygun bir modelle eğitilmesi işlemlerini içerir.

Veri Çekme Aşaması:
Selenium kullanılarak Hepsi Emlak sitesinden İstanbul Kağıthane bölgesindeki evlerin bilgileri ve fiyatları çekildi.
Veriler CSV formatında kaydedildi.

Model Eğitimi Aşaması:
Çekilen veriler üzerinde veri ön işleme adımları uygulandı (örneğin: eksik verilerin doldurulması, kategorik verilerin kodlanması, özellik mühendisliği vb.).
Veriler eğitim ve test setlerine ayrıldı.
Farklı regresyon veya makine öğrenimi modelleri denendi ve en uygun model seçildi.
Seçilen modelin performansı değerlendirildi.

Gelecek Çalışmalar:
Otomatik çalışan sistemler ve modeller geliştirmek için daha fazla deney yapmayı planlıyorum.
Veri çekme ve model eğitim süreçlerini optimize etmek için yeni yöntemler araştırılacak.
