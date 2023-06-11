# Windows Forms Kullanarak Motivasyon İçin Zar Atma Uygulaması

  Bu projeyi yapma amacım biliyorsunuz ki masabaşı iş yapan çok fazla çalışan var. Her gün aynı enerji ve motivasyon da olamayabiliyoruz. İşimize enerji dolu başlamak ve daha iyi çalışabilmek için şans üzerine günlük iş motivasyonu sözünü işe başlamadan önce öğreneceğiz ve kahvemizden bir yudum alıp güne güzel başlayabileceğiz. Ayrıca çift zar denk getiren personele gün içinde erken çıkma veya ödül sistemi kullanarak kendini şanslı hissetmesini sağlayabilirsiniz. Hem kişisel personel girişin bulunduğu hemde şirket sahibinin günlük söz ve hatırlatmalarını paylaşabileceği uygulamada şirket sahibi personele özel ve departmanlara özel günlük sözlerini paylaşabilecek. Eğlenceli bir şekilde güne başlayan personellerin ay sonundaki başarısını gözle görülür şekilde farkedeceksiniz.
# 1.pencere
ilk penceremizi açtığınızda karşınıza kullanıcı girişinden sonra gelen başlatma ekranıdır. Başlatma butonuna bastığımızda bir sonraki penceremiz açılır.

<img src="https://github.com/muruvvettopsakal/windows_forms_zaratmauygulamasi/assets/102542473/36b33174-bee7-4a5c-90e1-f90e41264e72" width="320" height="250">

# 2.pencere
Bu ekranda zar atma deneyimi yapmadan önceki ekranımızdır. Zar at dediğimiz anda zarları atmış oluruz ve random olarak gelen zarları görürüz.

<img src="https://github.com/muruvvettopsakal/windows_forms_zaratmauygulamasi/assets/102542473/e6b61195-20cd-45fe-9d8c-e70f1d4ba423" width="320" height="250">

# 3.pencere
Zarı attık ve artık gelen sayılarımıza bakarız.

<img src="https://github.com/muruvvettopsakal/windows_forms_zaratmauygulamasi/assets/102542473/a10fff6b-8af2-4099-b932-02f32e3dd75b"  width="320" height="250">

# 4.pencere
Ve artık günlük motivasyon sözünü görebilirsiniz.

<img src="https://github.com/muruvvettopsakal/windows_forms_zaratmauygulamasi/assets/102542473/0572becd-10af-48ed-80e9-17e52002c889" width="320" height="250">

## İçerik

 Ben uygulamamı tasarlarken Windows Forms kulllandım. Microsoft Visual Studio üzerinde geliştirdim. Sizde bu platformdan açabilirsiniz.
  Windows Forms, Microsoft tarafından geliştirilen bir framework'tür ve Windows tabanlı masaüstü uygulamaları geliştirmek için kullanılır. Windows Forms, kullanıcı arayüzü oluşturmayı ve etkileşimli Windows uygulamaları geliştirmeyi kolaylaştırır. Bu da bizim işimize gelir:)
 
 ## Proje kodları
 ## Giriş
 
 Giriş ekranımız için yani 1.pencere için giris.cs adında bir dosya oluşturdum. 
  
        private System.Windows.Forms.Button button1;
        private System.Windows.Forms.Label label1;
        private System.Windows.Forms.Label label2;
        
        Bu kod parçası giris.cs dosyamızda bulunacak. Windows Forms uygulamasında kullanılan özel alanların bildirimlerini içerir.
 </br>
 <strong>button1</strong>, bir düğme kontrolünü temsil eden özel bir alanı ifade eder.
   <strong>label1</strong> ve <strong>label2</strong>, etiket kontrollerini temsil eden özel alanları ifade eder.

Bu alanlar genellikle bir Windows Forms sınıfı içinde kullanılır ve bu sınıfta tanımlanan kontrollere erişmek için kullanılır. Yani,<strong> button1 </strong>,  <strong> label1</strong> ve <strong>label2 </strong> gibi kontrol elemanlarına erişim sağlamak veya bu kontrol elemanları üzerinde işlemler gerçekleştirmek için bu özel alanları kullanılır. Örneğin, düğmeye tıklandığında bir işlem gerçekleştirmek veya etiketlere metin atamak gibi.
## Form1
Form1.cs adında bir klasör oluşturdum. Form1 sınıfı Form sınıfından türetilmiş bir sınıftır ve zar uygulamasının ana formunu temsil eder.
Sonuçta bir zar simülasyonu gerçekleştiriyoruz. Bu simülasyonda button1 düğmesine tıklandığında rastgele iki zar atılacak ve sonuçlar görsel olarak görüntülenenecek. Aynı 2.penceredeki gibi.

Ben değişiklik olsun istedim ve sadece görsel değil işitsel olarakta kullanıcıya hitap etmeli, zar atım sesi ve özel çift zar atımları denk geldiğinde haberdar eden ses ekledim.
 <strong> SoundPlayer</strong> sınıfını kullanarak bir ses dosyası ekledim.

    
