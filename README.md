# 2019 Intern_Project

![image](https://user-images.githubusercontent.com/13971617/138435743-21801ef4-5774-4b9e-b1bb-bf359e746bc1.png)

`Şekil 1.1 Kullanıcı Giriş Ekranı`

Login yapıldığında id alınır, karakter oluşturulmak istendiği zaman kullanıcı adı ve şifre girildiğinde  web api’ye gönderilecek şekilde yapılmıştır.

![image](https://user-images.githubusercontent.com/13971617/138435775-8fb3f70c-6d71-4bb0-85de-96b1a8a2e063.png)

`
Şekil 1.2 Karakter Oluşturmak İçin WebApi'ye iletilecek adres.`

Giriş yapıldıktan sonra, kullanıcı adı girilmişse bu adres çağırıldığında yeni karakter başarıyla oluşturulur.


Asset store’den karakter paketleri ve harita indirildi. Karakter seçildi ve yürümesi için gerekli olacak script yazıldı. Karakterin yürüyebilmesi 
için, wasd veya yön tuşlarına tıklanması gerekir, bu tuşlardan gelen değerler ise Unity’de Horizantal ve Vertical olarak hazır sunulur. Bu değerler hareket için kullanılacağından değişkenlerde saklarız ve sürekli olarak güncellenir.

![image](https://user-images.githubusercontent.com/13971617/138435834-c6fc77e3-1dbb-4dd8-aec4-c699145031e2.png)

`Şekil 2.1 Karakter Hareket Kodu `
              
![image](https://user-images.githubusercontent.com/13971617/138435822-1d9267c6-0c2d-4c73-8e90-d4db1ca98b06.png)

`Şekil 2.2 Karakter Hareket`
              
												  
Üst tarafta görülen kod parçasındaki h ve v, önceden horizantal(h) ve vertical(v) değerleri kaydettiğimiz değişkenlerdir. Bu şekilde hareketin yönü belirlenir. V değeri pozitif yöndeyse ileri yönde, negatifse geri yönde ilerler. H değeri pozifise sağa, negatifse sola haraket eder.



![image](https://user-images.githubusercontent.com/13971617/138436508-ad0d4537-0a8e-4b5b-a712-54a6ed155396.png)

`Şekil 3 Düşman Hareket Kodu`

Düşmanın takibini sağlıyacak kod parçası yukarda görülmektedir. Kontrol edilen karakterin tagından bulur ve eğer o karakterin canı varsa karakteri takip eder. Canı bitene kadar takibi bırakmaz. Takip kodu bittikten sonra son testler yapıldı, takip ve hareketi sağlayan kodlarda sorun olmadığı görüldü. Karakter yeteneklerine başlandı ancak 20 günlük kısa bir stajda buraya kadar gelinebilindi.
