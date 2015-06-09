* SASS

```
// Using import...

$icon-spacing: 10px;
//$default-sort-order: a b c d e f g h i j k l m n o p q r s t u v w x y z !default;
//$icon-sprite-sort-by: 'width'; //width height size name none
//$icon-layout: 'vertical'; // vertical horizontal smart diagonal

@import 'icon/*.png';
@include all-icon-sprites;
// Or, if you are using a sprite map...
//$sprites: sprite-map('icon/*.png', $spacing: 10px);
```

* command

```
compass watch css/xxx.scss
```
