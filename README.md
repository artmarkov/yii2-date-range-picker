## Date range picker for Yii 2 

### Author vi mark https://github.com/webvimark/date-range-picker
#### Update Artur Markov

------------
Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist artsoft/yii2-date-range-picker "*"
```

or add

```
"artsoft/yii2-date-range-picker": "*"
```

to the require section of your `composer.json` file.

Configuration
-------------

If input in GridView

```php

use  artsoft\widgets\DateRangePicker;

<?php DateRangePicker::widget([
	'model' => $model,
	'attribute' =>'created_at',
        'format' => 'YYYY.MM.DD H:mm',
        'opens' => 'left',

]) ?>

```