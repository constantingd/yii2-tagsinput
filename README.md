## Установка

Via Composer

```bash
$ composer require constantingd/yii2-tagsinput
```

или 

```
"constantingd/yii2-tagsinput": "*"
```

в соотвествующую секцию `composer.json`.


## Использование

В файле view.

```php

<?php
use wbraganca\tagsinput\TagsinputWidget;
?>

<?= $form->field($model, 'tags')->widget(TagsinputWidget::classname(), [
    'clientOptions' => [
        'trimValue' => true,
        'allowDuplicates' => false
    ]
]) ?>

```

Еще про данный JS плагин: http://bootstrap-tagsinput.github.io/bootstrap-tagsinput/examples/
