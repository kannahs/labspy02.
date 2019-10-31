# labspy02.
Pengertian Kondisi If Else If Bahasa Python
Pada dasarnya, kondisi If Else If adalah sebuah struktur logika program yang di dapat dengan cara menyambung beberapa kondisi If Else menjadi sebuah kesatuan. Jika kondisi pertama tidak terpenuhi atau bernilai False, maka kode program akan lanjut ke kondisi If di bawahnya. Jika ternyata tidak juga terpenuhi, akan lanjut lagi ke kondisi If di bawahnya, dst hingga blok Else terakhir atau terdapat kondisi If yang bernilai True.

#Di Python ada 3 jenis pernyataan yang digunakan untuk percabangan, yaitu sebagai berikut.

![python](https://user-images.githubusercontent.com/56243857/67922773-59d5b500-fbde-11e9-99a2-47325159d0dc.png)

iftrue/false

#yang pertama kita akan membuat contoh bilangan yang memasukin bilangan satu sampai tiga
Bilangan1 = int(input("Masukkan Bilangan 1:")) Bilangan2 = int(input("Masukkan Bilangan 2:")) Bilangan3 = int(input("Masukkan Bilangan 3:"))

Berikutnya kita juga bisa membuat kondisi if int(Bilangan1) and (Bilangan1 > Bilangan3): seperti dibawah ini :
print("Nilai terbesarnya adalah :", Bilangan1) Terbesar = Bilangan1 NomBil = "Bilangan 1"

Selanjutnya kita juga bisa membuat kondisi elif (Bilangan2 > Bilangan3) and (Bilangan2 > Bilangan1): Seperti dibawah ini:
print("Nilai terbesarnya adalah :", Bilangan2) Terbesar = Bilangan2 NomBil = "Bilangan 2"

else: Terbesar = Bilangan3 NomBil = "Bilangan 3"

Selanjutnya menggunakan bilangan besar adalah
print("Bilangan yang terbesar adalah", NomBil, "dengan nilai", Terbesar)

#Selanjutnya kita mengetahui setelah RUN yang benar:

![pycharm1](https://user-images.githubusercontent.com/56243857/67922581-b2588280-fbdd-11e9-913b-baafb2e5dca4.PNG)

Pada Bahasa pemrograman python untuk membuat sebuah kondisi sama halnya dengan Bahasa pemrograman yang lain yaitu sama-sama menggunakan if, pada setiap pemrograman if berisi sebuah ekspresi logika menggunakan sebuah data yang telah dibandingkan seperti alur flowchart dibawah ini.

Contoh: 

![flowchart1](https://user-images.githubusercontent.com/56243857/67922547-98b73b00-fbdd-11e9-8f94-1479c637fdbc.PNG)
