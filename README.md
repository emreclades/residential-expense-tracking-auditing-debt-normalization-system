
# Residential Expense Tracking, Auditing, and Debt Normalization System

## Genel Bakış

Konut İçi Harcama Takibi, Denetimi ve Borç Normalizasyonu Sistemi, konut içi paylaşılan harcamaların sistematik olarak kaydedilmesi, denetlenmesi ve borç dengesinin sağlanması amacıyla geliştirilmiş bütünleşik bir yazılım platformudur.

Sistem, birden fazla kullanıcı arasında gerçekleşen finansal işlemlerin şeffaf, izlenebilir ve tutarlı biçimde yönetilmesini hedefler.


## Amaç ve Kapsam

Bu projenin temel amacı:

- Ortak harcamaların merkezi bir yapı altında toplanması  
- Kullanıcı bazlı harcama takibinin sağlanması  
- Borç ve alacak ilişkilerinin hesaplanması ve sadeleştirilmesi  
- Finansal verilerin doğrulanabilir ve denetlenebilir biçimde saklanması  

Sistem, küçük ölçekli yerleşim birimlerinden daha geniş kullanım senaryolarına kadar uyarlanabilir şekilde tasarlanmıştır.


## Temel Özellikler

- Çok kullanıcılı harcama yönetimi  
- Tarih, açıklama ve tutar bazlı kayıt sistemi  
- Kullanıcı bazlı toplam ve bakiye hesaplama  
- Borç normalizasyonu ve mutabakat hesapları  
- Denetlenebilir veri modeli  
- Genişletilebilir servis mimarisi  


## Mimari Yaklaşım

Sistem, modern yazılım geliştirme prensipleri esas alınarak tasarlanmıştır:

- Katmanlı mimari  
- Olay temelli iş akışları  
- Ayrık sorumluluklar  
- Ölçeklenebilir ve sürdürülebilir yapı  

Bu yaklaşım, sistemin uzun vadeli bakımını ve geliştirilmesini kolaylaştırmayı amaçlar.


## Sistem Bileşenleri

### İstemci Katmanı
- Web tabanlı kullanıcı arayüzü  
- Harcama girişi ve görüntüleme ekranları  
- Özet ve raporlama görünümleri  

### Sunucu Katmanı
- REST tabanlı API  
- İş kuralları ve doğrulama katmanı  
- Borç hesaplama ve mutabakat servisleri  

### Veri Katmanı
- İlişkisel veri modeli  
- Parasal değerler için hassas hesaplama  
- Geçmiş işlemlerin izlenebilirliği  


## Veri Modeli

Sistem aşağıdaki temel kavramlar etrafında yapılandırılmıştır:

- **User**: Sistemi kullanan birey  
- **Expense**: Gerçekleşen harcama kaydı  
- **Ledger**: Harcama ve bakiyelerin tutulduğu mantıksal defter  
- **Settlement**: Borç ve alacakların dengelenmiş hali  
- **Audit Log**: Sistem içi işlemlerin kayıtları  


## Borç Normalizasyonu

Sistem, kullanıcılar arasındaki borç ilişkilerini optimize etmek amacıyla borç normalizasyonu uygular.

Bu süreçte:
- Toplam harcamalar hesaplanır  
- Kullanıcı başına düşen pay belirlenir  
- Fazla veya eksik ödeme durumları tespit edilir  
- Gereksiz transferler minimize edilerek net borç durumu oluşturulur  


## Güvenlik ve Denetim

- Kimlik doğrulama ve yetkilendirme mekanizmaları  
- Hassas veriler için güvenli saklama  
- Denetim kayıtları ile işlem izlenebilirliği  
- Veri bütünlüğünü koruyan doğrulama süreçleri  


## Kurulum ve Çalıştırma

Kurulum adımları ve yapılandırma detayları ilgili dokümantasyon altında açıklanmıştır.

Sistem, container tabanlı dağıtım senaryolarını destekleyecek şekilde yapılandırılmıştır.


## Lisans

Bu proje **Apache License 2.0** kapsamında lisanslanmıştır.


## Katkı

Katkı süreçleri, kodlama standartları ve geliştirme yönergeleri proje dokümantasyonunda tanımlanmıştır.


## Not

Bu proje, konut içi finansal süreçlerin yönetimini standartlaştırmayı hedefleyen teknik bir çalışmadır.

