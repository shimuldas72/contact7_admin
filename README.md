Dynamic Form for Yii 2


Installation
------------

### Install With Composer

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require --prefer-dist shimuldas72/contact7_admin "dev-master"

```

Or, you may add

```
"shimuldas72/contact7_admin" "dev-master"
```

to the require section of your `composer.json` file and execute `php composer.phar update`.


For using it, add below code

For admin panel:
In your app config file add

```
'modules' => [
        'contact7' => [
            'class' => 'shimuldas72\forms\Forms',
        ]
    ],
```
