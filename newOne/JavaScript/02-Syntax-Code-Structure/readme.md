# JavaScript Kod yapısına Dair Birkaç Söz;
* Komutları oluşturabilmek için yazdığımız kod cümleleri ifade(statement) denir.
* İfadeler birbirine(;) işareti ile ayrılır.
* JS ifadelerin sonunda (;) konulması zorunlu kılmaz, kendisi otomatik olarak koyabilir.
* Ancak bu özelliğe güvenmemeliyiz. Kendimizi (;) koymaya alışmalıyız.
* Nedenlerini ilerledikçe öğreneceğiz.
* Yine de detaylı bilgi almak için [ECMAScript Automatic Semicolon Insertion](https://tc39.es/ecma262/#sec-automatic-semicolon-insertion) linkinden incelenebilir.
* Tanımlayıcı(Değişken, Fonksiyon vb.)adlandırma kuralları:
    * Tanımlayıcı adları harf, (_),($)işareti ile başlayabilir;diğer özel karakterler ya da rakamlarla başlayamaz.
    * İlk karakterlerden sonra (_),($), harf ya da rakam dışında herhangi bir karakter bulunamaz.
    * Tanımlayıcı adları küçük/BÜYÜK harf duyarlıdır.

* İsimlendirmede TÜRKÇE karakter KullanMAMAYA ALIŞMALISIN!
* İsimlendirme Yöntemleri(Her programlama dilinde geçerli)
    * Camle Case:
    En çok kullanılan isimlendirme yöntemlerinden biridir.
    Sözcüklerin ilk harfi büyük geri kalan harleri küçük yazılır.
    İki kullanımı vardır;
       * Upper Camel Case: Buna Pascal Case de denir. Her sözcüğün ilk harfi büyük, geri kalan herfleri küçük yazılır.Ör: AdSoyad, DogumTarihi, KdvOrani
       * Lower Camel Case: İlk sözcük tamamen küçük, geri kalan ların ise ilk harfi büyük geri kalanları küçük yazılır. Ör: adSoyad,dogumTarihi, kdvOrani
       * Snake Case:
        Sözcükler birbirinden (_)ile ayrılır. Upper ,Lower ve Screaming versiyonları vardır. Ör: Ad_Soyad, ad_soyad, dodum_taihi, DOGUM_Tarihi, AD_SOYAD, DOGUM_TARIHI
        * Diğer

    * JavaScript Name Conventions
     * Değişkenler:
      * Büyük Küçük harf duyarlı.
      * camelCase kullanılır, harfle başlanır.
      * İçinde ki değeri açıklayıcı niyelikte.
      * Mantıksal(Boolean)değişkenler genellikle is ya da has ,ifadesiyle  başlatılır.
      * İngilizce kavramlar kullan.
     * Fonksiyon ve Sınıf Metotları
       * Büyük küçük harf duyarlı.
       * camelCase kullanılır, harfle başlanır.
       * Genelde get, make, apply, gibi emir kipi le başlanır.
    * Sabitler:
       * Büyük küçük harf duyarlı.
       * Screaming Snake Case kullanılır.
       * Genelde en üstte olur.
    * Sınıflar:
       * Büyük küçük harf duyarlı.
       * PascalCase kullanılır, harfle başlanır,
       * Sınfın işlevselliğini açıklayıcı nitelikte.
    * Private:
       * _ ile başlar.

     * Resmi Dökümantasyon: [ECMAScript Official Documentation](https://tc39.es/ecma262)

* MDN Javascript Tutorial: [MDN JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)