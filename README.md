# E-Ticaret Müşteri Memnuniyeti Analizi ve Tahmini

Bu proje, Shopzilla (takma ad) adlı bir e-ticaret platformundaki müşteri hizmetleri etkileşimlerini analiz etmek ve müşteri memnuniyeti puanlarını tahmin etmek amacıyla hazırlanmıştır. Proje, Keşifsel Veri Analizi (EDA), görselleştirme ve makine öğrenimi sınıflandırma tekniklerini içermektedir.

---

## Veri Seti Hakkında

Veri seti, bir aylık süre boyunca müşteri memnuniyeti puanlarını yakalayan bir e-ticaret platformundan oluşturulmuştur. Veri seti, Faker kütüphanesi ile simüle edilmiş olup gerçek bilgiler içermemektedir.


## Veri Sütunları ve Tanımları

| **Sütun Adı**             | **Tanım**                                             
| **Benzersiz Kimlik**       | Her kayıt için benzersiz tanımlayıcı                   
| **Kanal Adı**              | Müşteri hizmetleri kanalının adı                        |
| **Kategori**               | Etkileşim kategorisi                                    |
| **Alt Kategori**           | Etkileşimin alt kategorisi                              |
| **Müşteri Yorumları**      | Müşteri tarafından sağlanan geri bildirim               |
| **Sipariş Kimliği**        | Etkileşimle ilişkili siparişin tanımlayıcısı            |
| **Sipariş Tarihi Saati**   | Siparişin tarihi ve saati                               |
| **Sorun Şu Adreste Bildirildi** | Sorunun bildirildiği zaman damgası                 |
| **Sorun Yanıtlandı**       | Sorunun yanıtlandığı zaman damgası                      |
| **Anket Yanıt Tarihi**     | Müşteri anketi yanıt tarihi                             |
| **Müşteri Şehri**          | Müşterinin şehri                                       |
| **Ürün Kategorisi**        | Ürün kategorisi                                         |
| **Ürün Fiyatı**            | Ürünün fiyatı                                          |
| **Bağlantılı İşlem Süresi**| Etkileşimin işlenmesi için gereken süre                |
| **Temsilci Adı**           | Müşteri hizmetleri temsilcisinin adı                   |
| **Denetçi**                | Denetleyicinin adı                                     |
| **Müdür**                  | Yöneticinin adı                                        |
| **Görev Süresi Kovası**    | Kategorilendirilmiş ajan görev süresi                  |
| **Ajan Vardiyası**         | Ajanın vardiya zamanlaması                             |
| **CSAT Puanı**             | Müşteri Memnuniyeti Puanı                              |




## Kullanılan Araçlar

- **Programlama Dili:** Python
- **Kütüphaneler:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

