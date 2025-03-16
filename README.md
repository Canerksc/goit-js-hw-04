# goit-js-hw-04

<!----------------------------------------------------------------Görev 1. Ürünlerin Paketlenmesi-------------------------------------------------------->

Bu görevi task-1.js dosyasında tamamla

isEnoughCapacity(products, containerSize) adında bir fonksiyon yaz, bu fonksiyon verilen ürünlerin tümünün konteynıra paketlerken sığıp sığmayacağını hesaplar.

Fonksiyon iki parametre alır:

products — Ürünlerin adlarını içeren ve miktarlarını değer olarak içeren bir nesne. Örneğin, { apples: 2, grapes: 4 }.
containerSize — Konteynerin içine sığabileceği maksimum ürün miktarı.
Fonksiyon, ürünlerin konteynıra sığıp sığmayacağını kontrol ederek sonucu döndürmelidir. Yani, products nesnesindeki toplam ürün miktarını hesaplayıp bu miktarın containerSize'a eşit veya daha az olduğunda true, aksi takdirde false değerini döndürmelidir.

<!----------------------------------------------------------------Görev 2. Kalori Hesaplama-------------------------------------------------------------->

Bu görevi task-2.js dosyasında tamamla.

calcAverageCalories(days) adlı bir fonksiyon yaz, bu fonksiyon hafta boyunca sporcu tarafından tüketilen kalori miktarının günlük ortalama değerini döndürür. Fonksiyon tek bir parametre bekler: days — bir dizi obje. Her obje, sporcu tarafından o gün tüketilen kalori miktarını açıklayan gün ve calories özelliklerine sahiptir.

<!-----------------------------------------------------------------Görev-3 Oyuncu Profili
----------------------------------------------------------------->

Bu görevi task-3.js dosyasında tamamla

profile nesnesi, bir oyun platformundaki kullanıcının profiline aittir. Özellikleri arasında profil adı username ve oyunda geçirilen playTime olarak belirtilen aktif saatler bulunmaktadır.

const profile = {
username: "Jacob",
playTime: 300,
};

profile nesnesini özellikleriyle çalışmak için metodlarla tamamlayın.

changeUsername(newName) metodu, bir dizeyi (yeni ad) newName parametresi olarak almalı ve username özelliğinin değerini yeni değerle değiştirmelidir. Hiçbir şey döndürmez.
updatePlayTime(saatler) metodu, bir sayıyı (saat miktarı) hours parametresi olarak almalı ve playTime özelliğinin değerini artırmalıdır. Hiçbir şey döndürmez.
getInfo() metodu, <Username> has <amount> active hours! formatında bir dize döndürmelidir, burada <Username>, profil adıdır ve <amount>, oyun saatlerinin miktarıdır.
