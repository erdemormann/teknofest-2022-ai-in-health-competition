<p align="center">
  <a href="https://www.teknofest.org/en/competitions/competition/34">
    <img src="https://cdn.teknofest.org/media/uploads/2023/02/22/saglkta-yz.png" alt="Teknofest" width="270">
  </a>
</p>

# Teknofest 2022 Sağlıkta Yapay Zeka Yarışması

## Teknofest 2022 - Veri Ön İşleme Projesi

**Teknofest 2022 Sağlıkta Yapay Zeka Yarışması için mamografi görüntülerinin ResNet algoritması için uygun formata getirilmesi ve mamografi görüntülerinin ön işlemesinin yapılması.**

Read this in other languages: [English](https://github.com/erdemormann/teknofest-2022-ai-in-health-competition/blob/main/README.md)

Geçtiğimiz Teknofest etkinliğinde Sağlıkta Yapay Zeka Yarışması kapsamında geliştirdiğim veri ön işleme projesini sizinle paylaşmak istiyorum. Proje kapsamında .dcm uzantılı medikal görüntü verilerinin işlenmesi ve analizi için geliştirdiğim özel önişleme kodlarını sizlerle paylaşıyorum.

Projemde, sağlık verilerini daha iyi işlemek ve analiz etmek amacıyla görüntü önişleme adımlarını içeren kodlar geliştirdim. 
Bu kodlar sayesinde, .dcm uzantılı dosyaları .png formatına çevirmek, görüntü üzerinde bulunan fotoğraf açı detayları gibi istenmeyen yazıların derin öğrenme algoritmaları için görüntü üzerinden kesildi, görüntüleri ResNet algoritması için yeniden boyutlandırmak ve renk kanalları arasındaki farklar azaltıldı. Ayrıca, veri bütünlüğünü korumak adına görüntülerin isimlendirme işlemleri ve dosya düzenlemeleri gerçekleştirildi.

Algoritmayı geliştirirken daha küçük bir veri seti ile çalıştım sonrasında algoritma tüm veri seti üzerinde uygulanmıştır. 
Tüm veri seti 16000 .dcm dosyasından oluşmaktadır.

**Öne Çıkan Özellikler:**

+ .dcm uzantılı dosyalar .png formatına çevrildi
+ Görüntüler üzerinde yazılı fotoğrafın açı bilgisi görüntü üzerinden kesildi.
+ Aykırı görüntüler silindi algoritmanın daha iyi bir eğitim ve öğrenim yapması için silindi.
+ Görüntülerin boyutları normalize edilerek, veri bütünlüğü sağlandı.
+ Farklı renk kanallarının birbirine eşitlenmesi ve görüntü kalitesinin iyileştirilmesi amaçlandı.
+ Özelleştirilmiş isimlendirme ve dosya düzenlemeleri ile veri yönetimi kolaylaştırıldı.
+ Geliştirilen kodlar, veri ön işleme adımlarını otomatikleştirdi ve analiz için daha uygun hale getirdi.

**Bu proje sayesinde, sağlık verilerinin daha iyi yönetilmesi ve işlenmesi hedefine adım attık.** 

Kodlarımı GitHub üzerinde paylaştım, böylece bu alanda çalışan diğer arkadaşlarımızın da faydalanabileceği bir kaynak oluşturmayı amaçladım. Umarım benzer çalışma gerçekleştirenler için faydalı olur.
