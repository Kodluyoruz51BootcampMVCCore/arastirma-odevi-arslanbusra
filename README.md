# Araştırma Ödevi


1. Solid Prensiplerini Öğren.
2. Microsoft Build 'den 2 etkinlik araştır.
3. Microsoft Build 2020 yeniliklerini Araştır.
4. Takip Ettiğin 2 yazılımcıyı araştır.
5. Devler Azure'da araştır [Eğitim-Workshop]
6. Yazılım ile ilgili Yarışmaları araştır (Örneğin: GGJ)


**Solid Prensipleri**

1. Bir sınıfın sorumluluğu sadece kendi görevi olmalıdır. Başka sınıfların sorumluluğunu
    üstlenmemelidir. Örneğin bir lokantada servisi yapan ve yemeği pişiren sınıflar ayrı ayrıdır.
    Aşağıda örnekle ifade edilmiştir.
    
    ![11](https://user-images.githubusercontent.com/66273342/84737075-d4a5e180-afaf-11ea-87c8-6cecfd601bdc.PNG)

2. Bir programın, uygulamanın geliştirmeye açık ancak değiştirmeye kapalı olması özelliğidir.
    Örneğin print işlemini yapan bir interface tanımladık. Bu şekilde değişikliğe gerek olmadan
    yeni gelen yazıcılar print özelliğini interface ile kazanmış oldu.
    
    ![12](https://user-images.githubusercontent.com/66273342/84737406-8a713000-afb0-11ea-91f5-711436991710.png)

    ![13](https://user-images.githubusercontent.com/66273342/84737433-9a890f80-afb0-11ea-9ef5-00ffdc75bb05.png)


3.Sırf işlemler birbirlerine benzedikleri için aynı çatı altında toplanmaz. Örneğin aşağıdaki
örnekte müşteriler için IBAN’a gerek vardır fakat öğrenciler için IBAN eklenmesi gerekmez.

   ![14](https://user-images.githubusercontent.com/66273342/84737463-a674d180-afb0-11ea-87f7-0e7f38d1aeb7.png)


4.Sınıflara gerekli method ve arayüzlerin tanımlanması gerekmektedir. Gereksiz eklentilerden
kaçınılmalıdır. Bunun için bir önceki örnek de verilebilir. Her sınıf için gerekli işi yapan arayüz
tanımlandı.

   ![15](https://user-images.githubusercontent.com/66273342/84737562-d58b4300-afb0-11ea-8ff4-6eba0a2c81f8.png)


5.Alt sınıflarda yapılan değişiklikler üst sınıfları etkilememelidir. Yani birbirlerine bağımlılıkları
olmamalıdır. Yazdırma örneği bunun için uygundur. Yazdırmayı bir sınıf üzerinde yapıyoruz fakat
bağımlılıkları bir interface üzerindedir. Yani üst sınıf(class Print) bu işlemde yazıcılara bağlı
değildir.

   ![16](https://user-images.githubusercontent.com/66273342/84737582-e045d800-afb0-11ea-896e-2ab478489ecd.png)

   ![17](https://user-images.githubusercontent.com/66273342/84737607-e936a980-afb0-11ea-91c1-050262e5a5a1.png)

**.NET Core 3.1'deki yenilikler**

.NET Core 3.1 ile ilgili en önemli özellik, uzun vadeli bir destek (LTS) sürümüdür.

Uzun Süreli Destek (LTS) nedir?

Microsoft bunu üç yıl içinde destekliyor, böylece uygulamalarımızı .NET Core 3.1'e taşıyabiliriz. Bu
öneriyi aşağıdaki analizlerle inceleyebiliriz.

Sürüm notu

.NET Core 3.0 3 Mart 2020'de kullanım ömrü dolmuş.

.NET Core 2.2 Kullanım ömrü 23 Aralık 2019.

.NET Core 2.1 21 Ağustos 2021'de kullanım ömrü dolmuş.

MacOS uygulaması

AppHost ayarı varsayılan olarak devre dışıdır. AppHost ayarı etkinleştirildiğinde, .NET Core
oluşturduğunuzda veya yayınladığınızda yerel bir Mach-O yürütülebilir dosyası oluşturur.
Uygulamanız, dotnet run komutuyla kaynak kodundan çalıştırıldığında veya Mach-O yürütülebilir
dosyasını doğrudan başlatarak appHost bağlamında çalışır. kullanıcının çalışma zamanına bağlı bir
uygulamayı başlatabilmesinin tek yolu dotnet <dosyaadı.dll> 'dir.


Windows Formları

Visual Studio Designer Toolbox'ta bir süredir kullanılamayan Windows Forms'da. Bunlar, .NET
Framework 2.0'daki yeni denetimlerle değiştirildi. Bunlar .NET Core 3.1 için Masaüstü SDK'sından
kaldırılmıştır. Araç kutusunda tasarımcılar değiştirildi. Bunlardan biri DataGridView. Yani bu öneri
uygulamamızı güncellemektir.

C ++ / CLI

C ++ / CLI ("yönetilen C ++" olarak da bilinir) projeleri oluşturmak için destek eklendi.
Bu iş yükü Visual
Studio'ya iki şablon ekler:

- CLR Sınıf Kütüphanesi (.NET Core)

- CLR Boş Proje (.NET Core)


Hafta içinde katıldığım etkinlik;


1.Damla Alkan anlatımı ile Yapay Zeka ; Azure Cognitive Search ile dökümanlarımızı Azure
Bulut Storage’e yükleyerek bu dökümanlarla görüntü işleme,metin analizi yapabilmeyi
deneyimledik. Bulutta var olan yapa zeka hizmetlerini kullandık. Sonrasında makine
öğreniminden bahsettik ve eğitim boyunca AI(Yapay Zeka),ML(Makine öğrenimi),DL(Derin
öğrenme) kavramlarının üzerinde durduk.


Takip edilebilecek yazılımcılar;

1.Engin Demiroğ

2.Sadık Turan


