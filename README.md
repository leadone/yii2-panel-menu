Виджет "Вертикальное меню bootstrap"
==================================

Реализация бокового вертикального меню, на основе компонента <a href="http://getbootstrap.com/components/#panels" target="blanc">Bootstrap panels</a>


Установка:
------------

Установка производится с помощью [composer](http://getcomposer.org/download/).

Запустите
```
composer timurmelnikov/yii2-panel-menu:*
```

или добавьте 
```
"timurmelnikov/yii2-panel-menu": "*"
```
в секцию require файла `composer.json` Вашего приложения.

##Использование:
В представлении, где будет использоваться yii2-panel-menu, подключить:
``` php
use timurmelnikov\widgets\PanelMenu;
```
Вывести виджет:
``` php
echo ShowLoading::widget(['loadingType' => 1]);
```

