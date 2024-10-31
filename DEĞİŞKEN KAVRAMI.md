# DEĞİŞKEN KAVRAMI
# Tanım
Yazılım dilinde değişken, bir değer saklamak için kullanılan bir isimlendirilmiş alan veya bellek parçasıdır. Değişkenler, programların çalışması sırasında farklı değerleri tutmak ve bu değerlere erişmek için kullanılır. Bizlerin günlük hayattaki her bir bilgisi, dijital ortamda veri olarak isimlendirilmektedir. Bu veriler programlama dillerinde sabit olarak tanımlanmaktadır. Ancak, eğer bu veriler ile programlama dillerinde depolama işlemi yapılması veya çeşitli işlemler gerçekleştirilmesi isteniyorsa, değişkenden yararlanmamız gereklidir.

# Kullanım
Değişkenler, program içerisinde veri tutmak, hesaplamalar yapmak ve sonuçları saklamak için kullanılır. Örneğin, bir kullanıcının girdiği sayıyı saklamak için bir değişken oluşturabilirsiniz. Değişkenler, programlama dillerinde verileri depolamamıza olanak sağlayan yapılardır. Örneğin; bir isim, sayı veya herhangi bilgiyi Python'da depolamak istiyorsak değişken oluşturmamız ve istenilen veriyi değişkende tanımlamamız gereklidir. Tabii ki değişkenleri oluşturabilmemiz için yazım kurallarına dikkat etmemiz gerekiyor.

#  Değişken Tanımlama
Python'da değişken oluştururken hata almamak ve doğru bir şekilde tanımlama işlemi yapabilmek için bazı önemli kurallar vardır.

1. Değişkene veri atama işlemi yapmak istersek değişken yazıp eşittir kullanmamız gerekir.

Örnek: degisken="sayidegeri"

x=10

evAdresi="yurt"

3. Bir değişken asla sayı ile başlamaz fakat sayı ile bitebilir.

Örnek: 12numara="okulNo" ->   Yanlış

 numara12="okulNo" ->   Doğru

5. Değişken ismi birden fazla kelimeden oluşuyorsa kelimeleri ayırmak için alt çizgi (_) sembolü kullanılmalıdır. Ayrıca, Kelimeleri ayırmadan da ikinci kelimenin ve arda gelen tüm kelimelerin ilk harfi büyük olacak şekilde de yazılabilir. Araya boşluk konularak ayırma işlemi yaparsak eğer hatayla karşılaşırız ve kodumuz çalışmaz.

Örnek:
meyve adi="Elma" -> Yanlış

meyve_adi="Elma" -> Doğru

meyveAdi="Elma"

4. Programa ait ifadeler değişken olarak kullanılmamalıdır. Örneğin, for adında veya break isminde bir değişken oluşturursak hata alırız. Bunun sebebi, Python'da belirli bir görevi olan ve anlamı bulunan kelimelerin, değişken ismi olarak oluşturulamamasıdır.
   
Örnek:
for=[1,2,3,4]

6. Değişken isimlerinde Türkçe karakter kullanılmamalıdır.
   
Örnek:

gökçen=10 -> Yanlış

gokcen=10 -> Doğru

6. Değişken isimlerinde Büyük ve küçük harf duyarlılığı bulunmaktadır. Bu sebeple okunuşları aynı olan harf veya kelimeler birbirlerinden farklı verilere sahip olabilir. Örneğin defter ve Defter isimlerindeki değişkenler birbirlerinden farklı değişken isimleridir.
   
Örnek:

Küçük e değişkeni ve değeri 25
e=25

Büyük e değişkeni ve değeri 14
E=14


# Türler
Değişkenlerin farklı türleri vardır:

Tamsayı (integer): Tam sayıların verilerini temsil eder.

Örnek:
sayi=49

Ondalık sayı (float): Ondalıklı veya gerçel sayıları temsil eder.

Örnek:
sayi=10.5

Not: Ondalıklı ifadeleri tanımlarken ondalık noktasını kullanmalıyız, virgül kullanılmaz.

Bool: Doğru ve yanlış ifadelerin tanımlanmasında kullanılır. Bu veri tipinin alabileceği 2 farklı değer vardır: True; eylemin gerçekleştirildiğini, False ise gerçekleştirilmediğini analtır.

Örnek:
kapıAcıkmı=False

String: Karaktersel veya metinsel verileri ifade eder. Bu veriler tanımlanırken çift tırnak sembolü içinde yazarak tanımlanır.

Örnek:
isim="sise"

Kaynakça: Yılmaz ALACA ve Emine YALÇIN, Görüntü İşleme
ChatGPT

Daha fazla örnek için py dosyalarına bakınız.





