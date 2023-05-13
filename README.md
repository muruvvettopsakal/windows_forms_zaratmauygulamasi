# Windows Forms Kullanarak Zar Atma Uygulaması Yapımı
### Zar Atma Uygulaması amacı
  Amacımız tavla oyunundaki atılan zarların tavlada ne anlama geldiklerini öğrenmektir. Böylece rakiplerinizle yarışmadan önce zarların ne anlama geldiğini bilir,oyunu daha eğlenceli hale getirebilirsiniz.
# 1.pencere
ilk penceremiz açtığımızda karşımıza gelen başlatma ekranımızdır. Başlatma butonuna bastığımızda bir sonraki penceremiz açılır.
![1](https://github.com/muruvvettopsakal/windows_forms_zaratmauygulamasi/assets/102542473/161dc940-cae7-4f31-b361-b611af9d6c2c)
# 2.pencere
Bu ekranda zar atma deneyimi yapmadan önceki ekranımızdır. Zar at dediğimiz anda zarları atmış oluruz ve random olarak gelen zarları görürüz.![2](https://github.com/muruvvettopsakal/windows_forms_zaratmauygulamasi/assets/102542473/24cb5172-ec89-4d8e-80be-5fbd78358a33)
# 3.pencere
Zarı attık ve artık gelen sayılarımıza bakarız. örneğin;![3](https://github.com/muruvvettopsakal/windows_forms_zaratmauygulamasi/assets/102542473/aaa230f9-e0b2-493c-9a72-a725a9c59323)
 > 4-4 geldi yani <strong>"dörtcihar"</strong> bunu uygulamız bize söyleyecek.
# 4.pencere
![4](https://github.com/muruvvettopsakal/windows_forms_zaratmauygulamasi/assets/102542473/6ef281f8-4505-4b47-9670-a898a3ed5b1f)
> böylece gelen sayının 4-4 olması durumunda adının ne olduğunu öğrendik.
> <ul>
   TAVLADA ZAR ADLARININ TAMAMI
  
     <li> 1-1: Hep Yek;
     <li> 2-2: Dubara;
     <li> 2-1: yek-i dü;
     <li> 3-3: Dü Se;
     <li> 3-2: Seba-i Dü;
     <li> 3-1: Se Yek;
     <li> 4-4: Dört Cihar ("Dört Caar" gibi de okunur);
     <li> 4-3: Cihar-ü Se ("Caar-i Se" gibi de okunur);
     <li> 4-2: Cihar-i Dü ("Caar-i Dü" gibi de okunur);
     <li> 4-1: Cihar-ı Yek ("Caar-i Yek" gibi de okunur);
     <li> 5-5: Dü Beş;
     <li> 5-4: Cihar-ü Penc ("Caar-i Penc" gibi de okunur);
     <li> 5-3: Penc-ü Se;
     <li> 5-2: Penc-i Dü;
     <li> 5-1: Penc-i Yek;
     <li> 6-6: Dü Şeş;
     <li> 6-5: Şeş Beş;
     <li> 6-4: Şeş Cihar;
     <li> 6-3: Şeş-ü Se;
     <li> 6-2: Şeş-i Dü;
     <li> 6-1: Şeş-i Yek;
  </li>
  </ul>
### İÇERİK
Öncelikle projemizin içeriğinden ve nasıl açabileceğinizi açıklayacağım.
<li> Ben uygulamamı tasarlarken Windows Forms kulllanacağım. Nedir bu windows forms ? Neden bunu tercih ettim hemen ufak bahsedeyim.
  Windows Forms, Microsoft tarafından geliştirilen bir framework'tür ve Windows tabanlı masaüstü uygulamaları geliştirmek için kullanılır. Windows Forms, kullanıcı arayüzü oluşturmayı ve etkileşimli Windows uygulamaları geliştirmeyi kolaylaştırır. Bu da bizim işimize gelir:)

Windows Forms, aşağıdaki nedenlerle tercih edilebilirsiniz:

   <li> Hızlı Geliştirme: Windows Forms, hızlı bir şekilde kullanıcı arayüzü oluşturmayı sağlar. Tasarım araçları ve sürükle-bırak özellikleri ile görsel olarak arayüz elemanlarını düzenleyebilir ve kolayca kod ekleyebilirsiniz.

   <li> Büyük Kontrol Kütüphanesi: Windows Forms, geniş bir kontrol kütüphanesi sunar. Bu kontrol kütüphanesi, düğmeler, etiketler, metin kutuları, listeler, takvimler gibi birçok kullanıcı arayüzü elemanını içerir. Bu sayede zengin ve işlevsel kullanıcı arayüzleri oluşturabilirsiniz.

  <li>  Masaüstü Uygulamaları: Windows Forms, masaüstü uygulamaları geliştirmek için özel olarak tasarlanmıştır. Bu tür uygulamalar, yerel olarak çalışır ve kullanıcının bilgisayarında doğrudan yüklü olurlar. Windows Forms, yerel kaynaklara erişim sağlayabilir ve sistem bileşenlerini kullanabilir.

  <li>  .NET Framework Entegrasyonu: Windows Forms, .NET Framework ile bütünleşiktir. Bu, .NET Framework'ün sağladığı güçlü özellikleri kullanabilmenizi sağlar. Örneğin, veritabanı bağlantısı, veri bağlama, hata yönetimi gibi özelliklere kolayca erişebilirsiniz.

 <li>   Geniş Destek: Windows Forms, Microsoft tarafından desteklenen bir teknolojidir ve geniş bir topluluk tarafından kullanılır. Bu da demek oluyor ki, sorunlarınıza ve sorularınıza yanıtlar bulmak için kaynaklara, belgelere ve forumlara kolayca erişebilirsiniz.

>Windows Forms, hızlı ve kolay bir şekilde masaüstü uygulamaları geliştirmek isteyen geliştiriciler için iyi bir seçenektir. Ancak, web tabanlı uygulamalar veya mobil uygulamalar gibi farklı platformlarda çalışan uygulamalar için farklı teknolojiler veya framework'ler kullanmanız gerekebilir.
</li>


## Bu çalışmam da hangi programı kullananacağım?
Microsoft Visual Studio
 
 # ŞİMDİ GELELİM PROJEDEKİ KULLANACAĞIMIZ KODLARDAN BAHSETMEYE
 ## Giriş
 
 Giriş ekranımız için yani 1.pencere için giris.cs adında bir dosya oluşturmayı düşünüyorum. 
  
        private System.Windows.Forms.Button button1;
        private System.Windows.Forms.Label label1;
        private System.Windows.Forms.Label label2;
        
        Bu kod parçası giris.cs dosyamızda bulunacak. Windows Forms uygulamasında kullanılan özel alanların bildirimlerini içerir. Asıl temel mantığımız bunu oluşturmak olmalı.

 button1, bir düğme kontrolünü temsil eden özel bir alanı ifade eder.
    label1 ve label2, etiket kontrollerini temsil eden özel alanları ifade eder.

Bu alanlar genellikle bir Windows Forms sınıfı içinde kullanılır ve bu sınıfta tanımlanan kontrollere erişmek için kullanılır. Yani,<strong> button1 </strong>,  <strong> label1</strong> ve <strong>label2 </strong> gibi kontrol elemanlarına erişim sağlamak veya bu kontrol elemanları üzerinde işlemler gerçekleştirmek için bu özel alanları kullanabilirsiniz. Örneğin, düğmeye tıklandığında bir işlem gerçekleştirmek veya etiketlere metin atamak gibi.
## Form1
Form1.cs adında bir klasör oluşturacağım. Form1 sınıfı Form sınıfından türetilmiş bir sınıftır ve zar uygulamasının ana formunu temsil eder.
Sonuçta bir zar oyunu simülasyonu gerçekleştiriyoruz.Bu simülasyonda button1 düğmesine tıklandığında rastgele iki zar atılacak ve sonuçlar görsel olarak görüntülenenecek. Aynı 2.penceredeki gibi.

Ben değişiklik olsun istedim ve sadece görsel değil işitsel olarakta kullanıcıya hitap etmeli, zar atım sesi ve özel çift zar atımları denk geldiğinde (1-1, 2-2, 3-3, 4-4, 5-5, 6-6) haberdar eden ses eklemeyi düşündüm.
 <strong> SoundPlayer</strong> sınıfını kullanarak bir ses dosyası ekleyeceğim.
 
 Genel anlamda kullanacağım ve önemli olan kısımlardan bahsettim. Artık projeyi çalıştırıp inceleyebileceksiniz. 
    
