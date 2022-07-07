# Week 4 Assignment for Enuygun PHP Bootcamp

## ARAŞTIRMA
- Test Driven Development ve Behaviour Driven Development arasındaki farkı açıklayınız.
  - TDD , Test Odaklı Geliştirmedir. Bu, belirtilen işlevsellik mevcut olmadığı için başarısız olan bir test yazmak, ardından testi geçebilecek en basit kodu yazmak, ardından çoğaltmayı kaldırmak için yeniden düzenleme yapmak vb. anlamına gelir.
  - BDD , Davranış Odaklı Geliştirmedir. Bu, özellik mevcut olmadığı için başarısız olan yürütülebilir bir belirtim oluşturmak ve ardından belirtimi geçebilecek en basit kodu yazmak anlamına gelir.

- Unit Test nedir? Unit Test nasıl yapılır?
  - Unit test uygulamamızın küçük bir parçasını uygulamanın geri kalanından bağımsız bir şekilde çalıştırarak bu parçanın davranışını doğrulayan bir metoddur.

## SYMFONY KONSOL UYGULAMASI OLUŞTURMA (20 puan)
1 ile N arası rastgele pozitif  tamsayıların olduğu bir array içinden en küçük ve en büyük sayıyı bulup, bu sayıları ekrana bastıran bir konsol uygulaması yazınız. Buradaki N değeri konsol uygulamasından parametrik olarak alınacaktır. Dizideki rastgele tamsayılar PHP’nin random fonksiyonuyla oluşturulabilir.

Örnek: 
Konsol Uygulaması için Input: 7
//Random array değerleri: Array = {1,6,743,24,132,54,9}

Çıktı: 
En Büyük Sayı: 743
En Küçük Sayı: 1

## SYMFONY WEB UYGULAMASI OLUŞTURMA (60 puan)
Ders esnasında composer ile oluşturmuş olduğumuz ve twig template içeren Symfony uygulamasını Repo’ya yükleyiniz. Twig template aşağıdaki özellikleri barındırmalıdır:
- En az 2 parametreyi controllerdan almalı (parametrelerden bir tanesi mutlaka array olmalı)
- Ena z 1 asset içermeli (css / js) ve template içinde bu asset kullanılmalı
- Template içinde controllerden alınan çıktı mutlaka döngüde bastırılmalı