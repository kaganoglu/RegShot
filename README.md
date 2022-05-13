# RegShot Nedir & Nasıl Kullanılır ?

### RegShot Nedir

Regshot, windows üzerinde programlar eklenmeden, çalıştırılmadan, kaldırılmadan veya değiştirilmeden önce ve tüm bunlar yapıldıktan sonra kayıt defterinde anlık görüntü alır. Daha sonra bu kayıtları karşılaştırarak ne gibi değişiklikler olduğunu bizlere sunar. Regshot'ı birçok platformdan **ücretsiz** bir şekilde indirebilirsiniz.

Not: Programın Türkçe de dahil olmak üzere birçok dil seçeneği vardır.
(Örn. Link https://sourceforge.net/projects/regshot/)

### RegShot Nasıl Kullanılır
1- Programı indirdikten sonra uygun olan sürümü çalıştırınız.

![image](https://user-images.githubusercontent.com/65306271/168309267-1c8c8baf-5c1a-4733-ae82-fa65d2a127a4.png)

**Not:** Daha somut yaklaşabilmek için sizlere bir zararlı yazılım ile örnek üzerinden anlatacağım.

![malware-regshot](https://user-images.githubusercontent.com/65306271/168311773-832ce0b6-c10c-4f99-ba00-e2cb6468908a.png)

2- Zararlı yazılımı çalıştırmadan önce programımızı açıyoruz. Basit bir arayüze sahip olan programda işlemlerimizden önceki kaydı almak için **1st shot** butonuna basıyoruz ve işlemin tamamlanmasını bekliyoruz.

![regshot-1](https://user-images.githubusercontent.com/65306271/168312041-e3418f88-ddbd-4edf-b218-c6a4ac28a7d4.png)

![regshot-2](https://user-images.githubusercontent.com/65306271/168312240-85c538e7-389d-4eef-9c36-f3456c67997d.png)

3- Daha sonra işlemimizi yapıyoruz (zararlı yazılımı çalıştırıyorum), bir süre bekledikten sonra  **2nd shot**  butonuna basıyoruz ve işlemin tamamlanmasını bekliyoruz. İşlem tamamlandıktan sonra yeni bir buton çıkıyor.

**Not:** Karşılaştırma yapmadan önce çıktıyı hangi formatta almak istediğinizi **"Compare logs save as"** bölümünden seçebilirsiniz. Ben TXT olarak seçiyorum. Ayrıca çıktının kaydedileceği dosya yolunu da **"Output path"** bölümünden seçebilirsiniz.

4- Sonrasında ise 1. ve 2. kayıtları karşılaştırman için **compare** butonuna tıklıyoruz.

![compare](https://user-images.githubusercontent.com/65306271/168312445-cfdf3705-70ad-4da4-ae7a-705f7574d8d8.png)

5- İşlem tamamlandığında sonucu bize bir metin dosyasında çıktı olarak veriyor.

![finish](https://user-images.githubusercontent.com/65306271/168312828-23ce1a89-39a2-432a-a2ae-049394e2abfb.png)

6- Metin içerisindeki detayları birkaç farklı başlık altında listelemiş olduğunu görüntüleyebiliriz. Bunlar:

- Silinen keys'ler
- Eklenen keys'ler
- Silinen değerler
- Eklenen değerler
- Değiştirilen değerler
- Toplam değişiklik

Yapılan değişiklileri bu şekilde analiz edebilirsiniz.
