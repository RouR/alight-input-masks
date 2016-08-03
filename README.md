# angular light input money mask 


## Configuration


1. Import the ```alight_money.js``` script in your page. For example:

```
<script src="alight_money.js"></script>
```


## How to use

 - Example:

```html
<input type="text" name="field14" al-money="defaultMoney" >
```

- Define the number of decimals (default is 2):

```html
<input type="text" name="field14" al-money="dec5" money-decimals="5">
```

- Extended example:

```html
<input type="text" name="field14" al-money="custom1" money-decimals="1" money-decimal-delimiter="/" money-thousands-delimiter=" " money-currency="&:">
```

### Demo ###

_See more usage examples in the [Demo page](http://rour.github.io/alight-input-masks/)_

### Links ###

Angular Light - http://angularlight.org/

Original directive for AngularJS 1x http://assisrafael.github.io/angular-input-masks/