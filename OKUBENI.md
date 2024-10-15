# PCANDbc
**PCANDbc: DBC Dosyası Yükleme ve CAN Mesaj Analizi Uygulaması**

Bu proje, Qt çerçevesini kullanarak bir DBC (Database CAN) dosyasını yükleyip analiz eden bir PCAN entegre uygulamasını içerir. Uygulama, araç sistemleri ile gerçek zamanlı veri alışverişi için CAN bus iletişimini kullanır.

## Proje Genel Bakışı
PCANDbc uygulaması, araç sistemlerinin izlenmesi ve kontrol edilmesi için sofistike bir arayüz sunar. Uygulama, PCAN (Peak CAN) donanımını kullanarak aracın CAN bus’ı ile çift yönlü iletişim sağlar.

## Özellikler
- Gerçek zamanlı CAN mesaj analizi  
- DBC dosyalarını yükleme ve yorumlama  
- Sinyal filtreleme ve yönetimi  
- Grafiksel verilerin görselleştirilmesi  
- Kullanıcı dostu arayüz tasarımı  
- PCAN donanımı ile entegre çalışma  

## Teknik Detaylar

### PCAN İletişimi
- Araç sensörlerinden (sıcaklık, nem vb.) gerçek zamanlı veri alır.
- İklim ayarlarını değiştirmek için kontrol komutları gönderir.
- Sağlam bir çalışma için hata yönetimi ve veri doğrulama uygular.

### QT Çerçevesi
- Kullanıcı arayüzünü oluşturmak için QT kullanır.
- Veri işleme sırasında pürüzsüz UI performansı için çoklu iş parçacığı (multi-threading) uygular.

### Veri İşleme
- CAN mesajlarının gerçek zamanlı ayrıştırılması ve yorumlanması.
- İstenilen iklim koşullarını sağlamak için algoritmik kontrol.

## Teknolojiler ve Araçlar
- QT Çerçevesi
- C++
- PCAN-Basic API
- CAN bus protokolü
- Sürüm kontrolü için Git

## Kurulum ve Yükleme
Projenizi kurmak ve çalıştırmak için aşağıdaki adımları izleyin:

1. **Gerekli Yazılımlar:**
   - QT
   - Git
   - PCAN-Basic API
2. Bu yazılımları bilgisayarınıza yükleyin.
3. Projeyi klonlayın:
   ```bash
   git clone https://github.com/yourusername/PCANDbc.git
   cd PCANDbc
