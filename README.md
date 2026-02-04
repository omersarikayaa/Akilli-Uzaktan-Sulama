🌱 Akıllı Uzaktan Sulama Sistemi (Arduino Tabanlı)

Bu proje, **Arduino** kullanılarak geliştirilmiş, bitkilerin sulama işlemini **otomatik ve kontrollü** şekilde gerçekleştiren bir **Akıllı Uzaktan Sulama Sistemi**dir.  
Sistem; toprak nem durumunu analiz ederek, yalnızca ihtiyaç duyulduğunda sulama yapar ve böylece **su tasarrufu** sağlar.

---

🎯 Projenin Amacı

Bu projenin temel amaçları şunlardır:

* 🌿 Bitkilerin sağlıklı şekilde sulanmasını sağlamak  
* 💧 Gereksiz su kullanımını önlemek  
* 🤖 Manuel sulama ihtiyacını ortadan kaldırmak  
* 📈 Sensör verilerine dayalı karar mekanizması oluşturmak  
* 🧠 Genişletilebilir ve geliştirilebilir bir sistem sunmak  

---

🛠️ Kullanılan Donanımlar

* Arduino Uno
* Toprak Nem Sensörü
* Röle Modülü
* Su Pompası
* Güç Kaynağı
* Bağlantı Kabloları
* Su Haznesi

---

💻 Kullanılan Yazılım ve Teknolojiler

* **Arduino IDE**
* **C / C++ (Arduino dili)**
* Analog sensör okuma
* Röle ile donanım kontrolü

---

⚙️ Sistem Çalışma Mantığı

1. Toprak nem sensörü, toprağın nem seviyesini ölçer  
2. Arduino, sensörden gelen veriyi analiz eder  
3. Nem seviyesi belirlenen eşik değerin altındaysa:
   * Röle aktif edilir
   * Su pompası çalışır
4. Toprak yeterli neme ulaştığında:
   * Sulama otomatik olarak durdurulur  

📌 Sistem tamamen otomatik çalışır ve kullanıcı müdahalesine gerek duymaz.

---

🔌 Devre Bağlantı Şeması

Arduino, nem sensörü ve röle bağlantılarını gösteren devre şeması aşağıda yer almaktadır:

![Devre Şeması](images/1-devre%20bağlantı%20şemasi.png)

---

🧠 Kesikli Su Algoritması

Sulama işlemi sürekli değil, **kontrollü ve kesikli** şekilde yapılır.  
Bu yöntem, hem su tasarrufu sağlar hem de toprağın aşırı sulanmasını önler.

![Kesikli Su Algoritması](images/2-kesikli%20su%20algoritmasi.png)

---

🏗️ Projenin Kurulu Hali

Aşağıda sistemin fiziksel olarak kurulmuş ve çalışmaya hazır hali görülmektedir:

![Projenin Kurulu Hali](images/3-projenin%20kurulu%20hali.png)

---

📊 Anlık Nem Takibi

Sistem, toprak nem durumunu **anlık olarak ölçer** ve Arduino üzerinden sürekli takip eder.

![Anlık Nem Takibi](images/4-anliknemtakibi.png)

---

🧑‍💻 Arduino IDE Üzerinden Kod Takibi

Arduino IDE üzerinde yazılan kodlar ile:

* Sensör verileri okunur
* Röle kontrol edilir
* Sulama kararları alınır

![Arduino IDE Kod Takibi](images/5-ardunioidenemtakibi.png)


