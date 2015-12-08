# spektral-sass
Reusable sass mixins for use in my projects

## Shorthand

### alpha
```sass
alpha($amount);
```

### rotate 
```sass
rotate($deg);
```

### scale
```sass
scale($scaleX, $scaleY: $scaleX);
```

### shadow
```sass
shadow($spread: 5px, $blur: 0, $color: #000, $hOffset: inset, $vOffset: 0);
```

### roundedCorners
```sass
roundedCorners($radius: 5px);
```

### transparentBG
```sass
transparentBG($color, $alpha);
```

### gradient
```sass
gradient($topColor: #444, $bottomColor: #999);
```

## Transitions

### fadeTo
```sass
fadeTo($speed: 1s, $amount: 1, $easeType: linear);
```

## Animation

### fade
```sass
fade($speed, $start: 0, $end: 1, $count: 1);
```

## Responsive Grid

```css
.grid-example {

        @include gridContainer;

        .two-column {
            @include twoColumn;
        }
        .three-column {
            @include threeColumn;
        }
        .four-column {
            @include fourColumn;
        }
        .five-column {
            @include fiveColumn;
        }
        .six-column {
            @include sixColumn;
        }

        .sixty-column {
            @include column(60%);
        }

        .forty-column {
            @include column(40%);
        }
    }

```