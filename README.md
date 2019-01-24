# url_converter: widget for yii2 

# What does it do
rewrites the russian-language string to translit
example: ВсЕм привет!! => vsem-privet

## Installation
The preferred way to install this extension is through [composer](http://getcomposer.org/download/). Remember to refer to the [composer.json](https://github.com/kartik-v/yii2-widgets/blob/master/composer.json) for 
this extension's requirements and dependencies. 

### Install

Either run

```
$ php composer.phar require Eskadra/url_converter "*"
```

or add

```
"Eskadra/url_converter": "*"
```

to the ```require``` section of your `composer.json` file.

### how it works
```php
use Eskadra\url_converter;

echo url_converter::widget(
['message'=>'write something here']
);
```
