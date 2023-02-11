# AkilliBeyazBastonProjesi
 Bu projeyi Teknofest Yarışmasına katılmak için kısıtlı bir zamanda Dr. Öğr. Üyesi Selin SüAR Oral Hocamın isteği ile gerçekleştirdim.
 
 Süreç: Kısıtlı bir zamanda bir proje oluşturmak ve bu projeyi tamamlayıp bir prototip hazırlamamız gerekliydi. Bizde Teknofet yarışmasında yer alan "engelsiz yaşam" katagorisine hitaben bir proje geliştirmek ve bu projeyi prototiplemek istedik.
 
 Amaç: Bu projede genel anlamda Görme engelliler için akıllı beyaz baston geliştirme odaklandık. Beyaz baston üzerine çalışmaya başlamadan önce giyilebilir ve yapay zeka destekli fikirler üzerinde durduktan sonra, görme engelli bireyler üzerinde yaptığımız araştırmalar sebebiyle bu fikirden vazgeçtik. Görme engelli bireyler "hiç bir teknolojiye beyaz bastonumu değişmem" ve "beyaz baston görme engelli bireyin gözleridir" ifadelerine odaklanarak beyaz bastonun özellikleri üzerine çalışma yapmaya karar verdik.
 
 Genel anlamda beyaz baston projelerinde tek adet ultrasonik mesafe sönsörü ile karıdaki engeller algılanır. Lakin kişinin karşısındaki katı cisimleri(duvar, araba vb.) beyaz baston zaten algılamasını sağlamakta. Dolayısıyla biz beyaz bastonun algılayamadığı şeylere odaklanmak istedik.
 
 WeWalk, Projeyi yaparken özellikle WeWalk'tan esinlendik. WeWalk görme engelli bireyin omuz ve baş hizasını algılayabilmekte ve bastonun eksik lkısımlarını bu şekilde tamamlamaktaydı. Lakin WeWalk Kullanan kişiler üzerinde yaptığımız kısıtlı araştırmada bile, bu beyaz bastonun yeterli özellik sunamadığını VE ÇOK PAHALI olduğunu vurgulamak isterim.
 
 Projemizi versyonlara bölerek, çok sensörlü ve yapay zekalı kamera modülleri ve globalde standartlara sahip olan teknolojiler üretmek için belirli adımlar ürettik. 
 
 Bu Adımlar:
 
 beyaz baston ikel lakin gelişmiş bir görme engelli yardım sistemidir. Bir çok görme engelli
insan beyaz bastonu 'gözlerimiz' olarak tanımlamaktadır.

dolayısıyla hiçbir teknolojinin görme engelli bastonu yerine geçemeyeceğini benimseyerek
bu projeyi yapmalıyız. Buradan edindiğimiz bilgilere dayanarak yapacağımız projenin 
ana amacı görme engelli bastonunun yapamadığı veya yetersiz kaldığı durumları geliştirmektir.

proje, görme engelliler için ana proje olarak adlandırılacaktır, ve versyonlar halınde geliştirilecektir.
Bunun yanında 2 ana veryonu bulunacaktır. Bu iki ana versiyon farklı sekillerde projelendirilecek ve
farklı şekillerde sorun çözecektir.

v1 beyaz baston.

sensörler ile bildirim alarak geliştirme yapılan kartlardan gelen inputları yorumluyarak outputları kullanıcılara
iletmek üzerine gelişrilecektir. 

sensörlerin verdiği bilgilerin doğruluğu ve kararlılığı sonuçları çok etkileyeceği için doğru sensör seçimi çok önemlidir.


geliştirme versyonları.

v1 tek bir geliştirme kartına çok sensörlu (ultrasonic mesafe sonsörü) bir model yapılarak
 test edilecektir.

v1.1 tek bir geliştirme kartına çok sensörlu (lazer mesafe sonsörü) bir model yapılarak
 test edilecektir.

V1.2 yapılan iki modeldeki input ve output, perfonmas ve pil değerleri test edilecek ve
 uygun sensör ve sensör grupları test edilecektir.

V2 Gerekli sensör seçimleri yapıldıktan sonra kablolardan kurtulmak ve daha konforlu ve
 kullanımı kolay bir model oluşturmak için kablosuz haberleşme modullerinin ar-ge
 çalışması yapılacaktır. bu versyondaki en büyük sorun kablosuz haberleşme modüllerinin çalışma
 hızlarının yeterli olup olmayacaklarıdır. arge başarılı olursa diğer versyona geçilecektir.

V3 çoklu geliştirme kartlı ve daha çok sensörlü bir beyaz basyon geliştirme için ar-ge çalışması 
 yapılacaktır. Bu versyonda çok faklı cihazları birbirine bağlayacağız ve kablosuz haberleşmesni
 planlıyoruz, dolayısızlı güvenlik ve iletim protoköllerinin doğru ve günli olması
 en önemli durumdur.

V4 kullanıcıya sesli output verebilmesi için ar-ge yapılacaktır. Bu özellik görme engellilerin 
 çok fazla işine yarayacaktır. lakin bir çok geliştirme kartı doğrudan mp3 gibi formatlar 
çalamamaktadır. dolayısıyla orange pi yada rasberry pi 0 2w gibi cihazlar ile arge denemeleri yapılacaktır.

V5 sensörlerin ve gerekli teknolojilerin görme engelliler ile testi ve yorumlaması sonrasında
 gereksiz sensörler varsa çıkartılacak ve gerekirse sensör eklenecektir.

Bizim kısıtlı bir zamanımız ve bütçemiz olduğu için 5 adet ultrasonic mesafe sensörü ile çalışan bir prototip geliştirebildik. Bu prototip, merdivenleri algılayabiliyor, kişinin önünde düz bir engel olup olmadığını algılayabiliyor, kişinin yürüdüğü zeminde çukur veya çıkıntı olup olmadığını algılayabiliyor.

Prototip bireyin merdivende olduğunu algıladıktan sonra merdivenden iniyor mu çıkıyor mu bunu da alğılayabiliyor. Projeye merdiven inme yada çokma işlemi tamamlandı mı? kontrolunü vereçek fonksyonu zaman yetişmediği için eleyemedim. ayrıca beyaz bastonlar her ne kadar çukur ve çıkıntıları algılasalar bile bireylerin bu etmenlere yeterince hızlı tepki veremediğini gözlemledik ve olası kazaları engellemek için sesli uyarı eklendi.

![20220307_112713](https://user-images.githubusercontent.com/90801002/218228055-e46c74a7-36a6-47cd-892b-98a01a852093.jpg)

Proje geliştirmesi Üniversite yada Teknofest tarafından fonlanmama ve destek görmemesi nedeniyle sonlandırıldı.
