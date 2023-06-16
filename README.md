# Haber Portalı (Web API ve Angular Material Arayüz)
## Proje Hakkında

- Akdeniz Üniversitesi Bilgisayar Programcılığı Bölümü İnternet Programcılığı 2 Dersi Final Projesi
- Projede Genel ve Yönetici olmak üzere iki farklı arayüz bulunmaktadır. 
- Genel arayüzde içerik ve kullanıcı işlemleri bulunmaktadır. 
- Yönetici bölümünde ise sistemin kontrolü için yönetim paneli şeklinde tasarlanmıştır.
- Verilen proje  ödevi  için  gerekli görsel  tasarımı Angular  Material standartlarına uygun  olarak hazırlanmıştır.
- Veri tabanı olarak SQL Server kullanılmıştır. 
- Verilen proje ödevi için gerekli tablo ve  alan  tasarımları  yapılarak  veri  tabanı  şeması  hazırlanmıştır.  
- Tablolar  arası ilişkilendirmeler  belirtilmiştir.


### 20211129028-HavvaYuksel

### Yetkiler
- Admin 
    * [Haber ekleme, güncelleme, silme]
    * [Kategori ekleme, güncelleme, silme]
    * [Yorum görüntüleme, yorum yapma]
    * [Üye ekleme, güncelleme, silme]

- Üye Kullanıcı [Haberleri görüntüleme, yorum görüntüleme, yorum yapma]

- Genel Kullanıcı [Haberleri görüntüleme]

## Tablo Modeli

![Ekran Alıntısı](https://user-images.githubusercontent.com/122538510/236784778-2a9af3e1-6324-4f54-b980-53faeb204133.PNG)
![Ekran Alıntısı1](https://user-images.githubusercontent.com/122538510/236784782-5b9b20af-99dc-425c-91ff-296578ee37c7.PNG)

## Api Servisleri

![FireShot Capture 001 - Swagger UI - localhost](https://user-images.githubusercontent.com/122538510/236784785-38a1482a-e86d-462d-9dca-b17ffea21a01.png)

## Login Üye+Admin

![screencapture-localhost-4200-login-2023-06-14-19_48_51](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/027bdbcd-4da7-4c5e-bf03-00630a83fabe)

![screencapture-localhost-4200-login-2023-06-14-19_53_51](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/cc035676-15ab-425e-92e4-094250cdaf43)

## Anasayfa Genel

![screencapture-localhost-4200-2023-06-14-19_47_41](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/c2c18557-f897-497b-8194-8208e5deb07a)

## Anasayfa Üye Kullanıcı

![screencapture-localhost-4200-2023-06-14-19_54_00](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/313e1d85-4e1d-496b-a505-e115f4e8e77a)

## Anasayfa Admin Kullanıcı

![screencapture-localhost-4200-2023-06-14-19_49_40](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/8a998b55-d751-43c0-a4e3-533643cd9c8c)

## Kategoriye Ait Haberler Sayfası

![screencapture-localhost-4200-kategori-1-2023-06-14-19_48_34](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/550e4b76-da3f-4bb8-9f52-e771e1ffa4d4)

## Haber Detay Genel

![screencapture-localhost-4200-haber-28-2023-06-14-19_48_19](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/2aa2850c-b3f5-40ba-81b0-523e3311d499)


## Haber Detay Kullanıcı

![screencapture-localhost-4200-haber-28-2023-06-14-19_49_57](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/bd4f72ac-57b8-4e85-aad3-7ed5079c04a9)


## Admin Kategoriler Sayfası ( Ekle, HaberListele, Düzenle, Sil)

![screencapture-localhost-4200-admin-kategori-2023-06-14-19_50_11](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/89cd8fff-98dd-4e41-86d6-e03209a574b4)

## Admin Haberler Sayfası ( Ekle, KategoriSeç, KategoriListele, Düzenle, Sil)

![screencapture-localhost-4200-admin-haber-2023-06-14-19_53_07](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/1bc954c7-aba1-4ba9-86ba-5ab52423b3b5)


## Admin Üyeler Sayfası ( Ekle, Düzenle, Sil)

![screencapture-localhost-4200-admin-uye-2023-06-14-19_53_26](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/7539ce75-3ed7-4f7e-8e75-fe9baf0835bf)

## Kullanıcıya Ait Haberler Sayfası

![screencapture-localhost-4200-uyehaber-1-2023-06-14-20_27_22](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/0e7b5bdf-de03-4306-9837-152803542054)

![screencapture-localhost-4200-uyehaber-2-2023-06-14-20_27_05](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/4f381ee8-1f93-4ae3-a7f5-be4621f73773)

![screencapture-localhost-4200-uyehaber-3-2023-06-14-20_27_35](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/9d2c138f-056b-4cda-b7c7-c370ac73e55c)

## Üzerinde Haber Kayıtlı Olmayan Kategori Sayfası

![screencapture-localhost-4200-kategori-11-2023-06-14-19_56_25](https://github.com/20211129028-HavvaYuksel/20211129028-HavvaYuksel_Final/assets/122538510/2fcaabcb-1ad1-48d5-aa3c-9562e090a46f)




