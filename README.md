CKEditor widget for Yii Framework
============

Simple Yii CKEditor widget.

Adds CKeditor

Installation
------------

Copy this widget to Extensions folder or run the command in the console
```
git clone https://github.com/Victor8730/yii-ckeditor.git
```

Usage
-----

If not import class, call the widget 

```php
$this->widget('application.extensions.yii-ckeditor.CKEditorWidget', [
  'model'=>$model,
  'attribute'=>'body',
  'language'=>'ru',
  'name'=>'ckeditor-for-body',
  'id'=>'ckeditor-for-body',
   'editorTemplate'=>'full',
]);
```

If import the widget class file, call the widget:

```php
Yii::import('application.extensions.yii-ckeditor.CKEditorWidget');

$this->widget('CKEditorWidget', [
  'model'=>$model,
  'attribute'=>'body',
  'language'=>'ru',
  'name'=>'ckeditor-for-body',
  'id'=>'ckeditor-for-body',
   'editorTemplate'=>'full',
]);


```