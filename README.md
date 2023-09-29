# SwiftArrayKonuAnlatimi
Swift programlama dilinde diziler (arrays), birden fazla değeri saklamak ve bu değerlere erişmek için kullanılan önemli bir veri yapısıdır. Swift dizileri
aşağıdaki gibi tanımlanır ve kullanılır:

Dizi Tanımı (Array Declaration):
Swift'te bir dizi oluşturmak için "[]" içinde değerleri virgülle ayırarak tanımlarsınız. İşte bir dizi nasıl tanımlanır:
var sayilar: [Int] = [1, 2, 3, 4, 5]
Yukarıdaki örnekte, "sayilar" adında bir dizi oluşturduk ve içine tamsayı (Int) değerleri ekledik.
Diziye Değer Ekleme (Appending to an Array):
Bir diziye yeni bir değer eklemek için append() fonksiyonunu kullanabilirsiniz:
sayilar.append(6)
Bu komut, "sayilar" dizisine 6 değerini ekler.
Dizinin Elemanlarına Erişme:
Dizi elemanlarına erişmek için dizi adını ve indeksi kullanabilirsiniz. İndeksler 0'dan başlar. Örneğin:
let ilkEleman = sayilar[0] // Dizinin ilk elemanını alır (1)
Dizi Uzunluğunu (Count) Alma:
Bir dizinin eleman sayısını öğrenmek için count özelliğini kullanabilirsiniz:
let elemanSayisi = sayilar.count // Dizinin eleman sayısını alır (6)
Dizi İterasyonu (Dizi Üzerinde Döngü):
Dizi üzerinde döngü yapmak için for-in döngüsünü kullanabilirsiniz:
for sayi in sayilar {
    print(sayi)
}
Dizi Sıralama (Sorting):
Diziyi sıralamak için sort() fonksiyonunu kullanabilirsiniz:
sayilar.sort()
Dizi Filtreleme (Filtering):
Dizi elemanlarını belirli bir koşula göre filtrelemek için filter() fonksiyonunu kullanabilirsiniz:
let tekSayilar = sayilar.filter { $0 % 2 != 0 }
Yukarıdaki örnek, "sayilar" dizisinden sadece tek sayıları içeren yeni bir dizi oluşturur.
Swift dilinde diziler çok yönlüdür ve birçok farklı işlem için kullanılabilirler. Yukarıda verilen temel bilgiler, Swift dizilerini kullanmanıza yardımcı olacaktır.
