
# E-Ticaret Uygulaması (Java Spring MVC)

Bu proje, **E-Ticaret** platformu oluşturmak için geliştirilmiş bir Java Spring MVC uygulamasıdır.
Proje, **Model-View-Controller (MVC)** mimarisi ile yapılandırılmış ve **Spring Framework** kullanılarak inşa edilmiştir.
Kullanıcıların ürünleri görüntüleyebileceği, sepetlerine ürün ekleyebileceği ve satın alma işlemleri gerçekleştirebileceği
bir çevrimiçi mağaza uygulaması oluşturulmuştur.

## Gereksinimler

- **Java 11 veya üzeri**
- **Maven 3.6.0 veya üzeri**
- **Spring Boot 2.x**
- **IDE (IntelliJ IDEA, Eclipse, vs.) veya komut satırı kullanarak çalıştırma**
- **Veritabanı**: MySQL

### Klasör Açıklamaları:

- **controller/**: Kullanıcıdan gelen istekleri işleyen ve uygun model ve view ile yönlendiren sınıflar.  
- **model/**: Veritabanı ile etkileşimde bulunan ve uygulamanın veri yapılarını temsil eden sınıflar (örneğin, `Product`, `Order`, `User` gibi). 
- **service/**: İş mantığını yöneten sınıflar, genellikle Controller ile Model arasındaki bağlantıyı sağlar.
- **repository/**: Veritabanı işlemleri ile ilgilenen sınıflar, Spring Data JPA kullanılarak oluşturulmuş CRUD işlemleri burada yapılır.
- **config/**: Spring yapılandırma dosyaları, servislere dair konfigürasyonlar burada bulunur.
- **templates/**: Thymeleaf ile oluşturulmuş HTML dosyaları ve UI bileşenleri.
