# isimler ve ebced değerleri
## bazı isimlerin osmanlıca yazılışları ve ebced değerleri

```ihya.org``` adresinde bulunan (çoğu isim) osmanlıca kelimeleri çekerek ```isimler.csv```  dosyasına kaydettik.
daha sonra bu dosyayı ve oluşturduğumuz tabloyu (ebced- python dictionary) kullanarak, kelimelerin [ebced](https://tr.wikipedia.org/wiki/Ebced_hesab%C4%B1) değerlerini hesapladık.
son olarak, türkçe isimleri, osmanlıca isimleri ve ebced değerlerini  ```isimler_ve_ebced.csv``` isimli dosyada birleştirdik.
dosya içeriği şu şekildedir:

|türkçe isim|osmanlıca isim|ebced değeri|
| ------ | ------ | ------ |
|yakup| یعقوب|188|
|güneş| كونش|376|
|çağdaş| چاغداش|1309|
|bekir| بكر|222|
|bilal| بِلال|63|
|belkıs| بِلقیس|202|
|celal| جلال|64|
|cemil| جَمیل|83|
|cemile| جَمیله|88|
|cevahir| جواهر|215|
|cevriye| جورييه|234|
|hafız| حافظ|989|
|hamit| حامد|53|
|habip| حبیب|22|
|habibe| حبیبه|27|
|hasan| حسن|118|
|hüseyin| حسین|128|
|husna| حُسنی|128|
|hafsa| حَفصه|183|
|...| ...|...|
|...| ...|...|


```osmanlicaimla.com``` adresinde bulunan osmanlıca kelimeleri çekerek ```turkce_osmanlicakelimeler.csv```  isimli dosyaya kaydettik.
Bu dosya ```17000```'den fazla kelime ve osmanlica karşılığını içermektedir. dosya içeriği şu şekildedir:


|Osmalıca_yazılış|Türkçe_yazılış|
| ------ | ------ |
|آ|A|
|اعدا|â'dâ|
|اعداد|â'dâd|
|اعما|â'mâ|
|اعظم|a'zam|
|آب|âb|
|آبدار|âb|
|آباء|âbâ|
|آباد|âbâd|
|آبادان|âbâdân|
|...| ...|...|
|...| ...|...|

