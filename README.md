# teamworkExercise

Merhabalar, ortak bir kaç standart belirleyebilir. Bu kısım daha sonrasında güncellenecektir...

1) .html, .css dosyalarının isimlendirilmesi ve html dosyası içindeki title ve link içindeki kısımların doldurulması ile ilgili:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>xxx</title>
    <link rel="stylesheet" href="stylexxx.css" />
  </head>

  standart head kısmımızı bu şekilde oluşturup title a resim adımız link in href inede style yazısından sonra Büyük harfle başlayarak .css dosyamızı oluşturabiliriz.

Örnek verecek olursak Layout egzersizimiz için :

styleLayout.css oluşturulup,
layout.html açılıp içine 

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Layout</title>
    <link rel="stylesheet" href="styleLayout.css" />
  </head>

bu şekilde bir standart başlangıç yapılabilir.

2) her türlü egzersizimizden index.html sayfamıza dönebilmek için oluşturulacak MENU linki ve style bilgisi ile ilgili:

Yaptığımız egzersizlerin html sayfasının en altına </body> ' den hemen önce aşağıdaki kısmı,

<a href="index.html">MENU</a>

Style dosyalarına da aşağıdaki kısmı kopyalayıp bir standart oluşturabiliriz

a{
    position: fixed;
    top: 600px;
    left: 500px;
}