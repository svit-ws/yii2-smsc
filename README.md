SMSC Extension for Yii 2
========================
Extension for working with SMS services: smsc.ru, smsc.ua

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist svit-ws/yii2-smsc "*"
```

or add

```
"svit-ws/yii2-smsc": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php
$sms = new \svit\smsc\SMS(); 
$sms->send('+3801111111111', 'SMS text', $options);
?>```
