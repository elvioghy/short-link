# short-link
Merhaba ben [elvioghy](http://elvio.tech),
```txt
Bu gün sizlere arşivimde bulunan bir link kısaltma mini scriptini veriyorum.
İstediğiniz gibi düzenleyebilirsiniz, kodları yardım için kullanabilirsiniz.
```
## Kurulum;
```txt
sys/database.php içindeki kodları şu şekilde değiştirin:
```
```php
<?php
try {
    /*
    * Büyük harflerle yazılan kısımları güncelleyin.
    */
    $host="mysql:host=DB HOST;dbname=DB NAME;charset=utf8";
    $dbuser="DB USER NAME";
    $dbpass="DB PASSWORD";
    $db=new PDO($host, $dbuser, $dbpass);
} catch (PDOExpception $e) {
    echo $e;
}
?>
```
```txt
Kodları düzenledikten sonra, bilgilerini girdiğiniz veri tabanının phpMyAdmin kısmına girin,
zip'in içinde bulunan 'link.sql' dosyasını içe aktarın.
Ve scriptiniz kuruluma hazır, bir admin paneli vs. yoktur.
```
