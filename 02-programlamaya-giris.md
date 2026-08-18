## Programlamaya Giriş

Programlama, bilgisayara belirli bir görevi yerine getirmesi için verilen talimatlar bütünüdür. Bilgisayarlar kendi başlarına düşünemezler; yalnızca kendilerine verilen mantıksal komutları (algoritmaları) çok hızlı bir şekilde işlerler.

* **Makine Dili:** Bilgisayarın donanımının doğrudan anladığı `1` ve `0`'lardan oluşan (binary) dildir. İnsanların bu dilde kod yazması çok zor ve hata yapmaya açıktır.
* **Programlama Dili:** İnsanların anlayabileceği (genelde İngilizce temelli) komutların, bilgisayarın anlayabileceği makine diline çevrilmesini sağlayan aracı dillerdir. 
*

---

## Kod Nedir?
Kod yazmak bir talimat dizisi yazmaktır.

---

## Programlama Diliyle Neler Yapılabilir?

Programlama dilleriyle dijital dünyadaki pek çok farklı alanda çözümler üretilebilir ve sistemler geliştirilebilir:

* **Web Geliştirme:** İnternet siteleri, web tabanlı uygulamalar ve e-ticaret platformları oluşturulabilir (Örn: Front-end ve Back-end sistemleri).
* **Mobil Uygulama Geliştirme:** Akıllı telefonlar ve tabletler için iOS (Swift) veya Android (Kotlin, Dart/Flutter) tabanlı uygulamalar yazılabilir.
* **Veri Bilimi ve Yapay Zekâ:** Büyük veriler analiz edilebilir, makine öğrenmesi modelleri eğitilebilir ve yapay zekâ sistemleri geliştirilebilir.
* **Oyun Geliştirme:** 2D ve 3D bilgisayar veya konsol oyunları tasarlanıp programlanabilir.
* **Otomasyon ve Script Yazımı:** Tekrarlayan günlük işler, dosya düzenlemeleri ve veri aktarımları otomatikleştirilebilir.
* **Gömülü Sistemler ve IoT (Nesnelerin İnterneti):** Akıllı ev cihazları, robotik sistemler, mikrokontrolcüler (Arduino, Raspberry Pi) ve endüstriyel makineler kontrol edilebilir.

## Tümleşik Geliştirme Ortamı (IDE - Integrated Development Environment)

**IDE**, yazılım geliştiricilerin kod yazma, test etme, derleme ve hata ayıklama süreçlerini tek bir çatı altında toplamalarını sağlayan kapsamlı bir yazılım aracıdır.

Basit bir metin düzenleyiciden (Not Defteri vb.) farklı olarak, bir projenin tüm yaşam döngüsünü yönetmek için gerekli bileşenleri entegre biçimde sunar.

---

### Temel Bileşenleri

* **Kaynak Kod Editörü (Source Code Editor):** Kod renklendirme (syntax highlighting), otomatik kod tamamlama (IntelliSense) ve otomatik girintileme sunan metin düzenleme alanı.
* **Derleyici / Yorumlayıcı (Compiler / Interpreter):** Yazılan kaynak kodunu doğrudan IDE içerisinden çalıştırılabilir makine diline çeviren veya yürüten sistem.
* **Hata Ayıklayıcı (Debugger):** Kodu satır satır çalıştırarak (breakpoint koyarak) mantıksal hataları, değişken değerlerini ve bellek durumunu anlık inceleme imkânı veren araç.
* **Yapı Otomasyonu (Build Tools):** Proje bağımlılıklarını yöneten, kodu otomatik paketleyen ve derleme işlemlerini organize eden araçlar.
* **Sürüm Kontrol Entegrasyonu (Version Control):** Git gibi sistemleri doğrudan arayüz üzerinden (commit, push, pull, branch yönetimi) çalıştırma desteği.

---

### Popüler IDE ve Editör Örnekleri

* **VS Code:** Hafif, eklentilerle tam teşekküllü bir geliştirme ortamına dönüşebilen modern editör.
* **Visual Studio:** C++, C#, .NET ekosistemi için tasarlanmış kapsamlı profesyonel IDE.
* **JetBrains Ailesi (PyCharm, IntelliJ IDEA, CLion):** Python, Java ve C/C++ gibi dillere özel optimize edilmiş akıllı IDE'ler.
* **Android Studio:** Android mobil uygulamaları geliştirmek için kullanılan resmi IDE.
* **Xcode:** macOS ve iOS uygulamaları geliştirmek için Apple ekosistemine özel resmi ortam.

## .NET Framework

**.NET Framework**, Microsoft tarafından geliştirilen, Windows işletim sisteminde uygulamaların oluşturulmasını, dağıtılmasını ve çalıştırılmasını sağlayan kapsamlı bir yazılım geliştirme platformudur (framework).

---

### Temel Mimarisi ve Bileşenleri

* **CLR (Common Language Runtime):** .NET uygulamalarının çalışma zamanı motorudur. Bellek yönetimi (Garbage Collection), iş parçacığı (threading) yönetimi, istisna yakalama (exception handling) ve güvenlik denetimlerini yürütür.
* **FCL (Framework Class Library):** Veritabanı erişimi, dosya okuma/yazma, ağ iletişimi, veri yapıları ve kullanıcı arayüzü gibi standart işlevleri içeren zengin hazır sınıflar kütüphanesidir.
* **Çoklu Dil Desteği:** C#, VB.NET ve F# gibi farklı dillerde yazılan kodlar önce **IL (Intermediate Language)** adlı ortak ara koda, ardından CLR içerisindeki **JIT (Just-In-Time) Compiler** ile makine diline çevrilir.

---

### Temel Özellikleri

* **Windows Bağımlılığı:** Klasik .NET Framework yalnızca Windows işletim sisteminde çalışacak şekilde tasarlanmıştır *(Platform bağımsız modern geliştirme için günümüzde modern `.NET` / `.NET Core` kullanılır)*.
* **Dil Bağımsızlığı (Language Interoperability):** Farklı .NET dilleriyle yazılmış modüller aynı proje içerisinde bir arada sorunsuz çalışabilir.
* **Geniş Uygulama Alanı:** Masaüstü (WPF, Windows Forms), web (ASP.NET) ve web servisleri (WCF) geliştirmek için altyapı sunar.
.netframeworks:


