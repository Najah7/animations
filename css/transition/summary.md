# CSS Transition

## Description
CSS transitions allows you to change property values smoothly (over a given duration).

## basic properties
| Property | Description | Value Examples |
| --- | --- |
| transition-property | Specifies the name of the CSS property the transition effect is for | property-name/all |
| transition-duration | Specifies how many seconds or milliseconds a transition effect takes to complete | <n>s/<n>ms |
| transition-timing-function | Specifies the speed curve of the transition effect | ease, linear, ease-in, ease-out, ease-in-out |
| transition-delay | Defines when the transition effect will start | <n>s/<n>ms |

### transition-timing-function
- ease: Specifies a transition effect with a slow start, then fast, then end slowly (this is default)
- linear: Specifies a transition effect with the same speed from start to end
- ease-in: Specifies a transition effect with a slow start
- ease-out: Specifies a transition effect with a slow end
- ease-in-out: Specifies a transition effect with a slow start and end

## transition shorthand property
The `transition` property is a shorthand property for the four transition properties:
```css
transition: property duration timing-function delay;
```
multiple
```css
transition: property1 duration1 timing-function1 delay1, property2 duration2 timing-function2 delay2, ...;
```

## CSS Properties can be transitioned
animateable properties are numerical properties, such as width, height, margin, padding, font-size, etc...
[Detail](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties)
