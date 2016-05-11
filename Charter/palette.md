# Prologic Theme

You'll see a few blues and a few whites, if you have questions, ask. This document will be updated as additional colors are added.

Please note, black is not #000000 rather it is #212121 and white is not #FFFFFF rather it is #F7F7F7 for example.

Some random facts about the color palette.  The palette is named Prologic Theme as the theme is "keyed" from the "ProLogic Blue" which is the dark blue you would see on the prologic logo. The color sampled from the Prologic AI marketing materials is called Biscay #253664. The color varies slightly out in the wild, for example, the color on the TEAMS header seems to be the exact same blue but it is Astronaut Blue #1C4966. In this document I am using Biscay and ignoring Astronaut Blue.

###### A) it can visually port from the existing design to a new design

###### B) has good accessibility with regard to contrast and usability with minimum eye strain and

###### C) that it is organized and comprehensive

### Color Rules
- Biscay to Dark Pink
```scss
lighten(saturate(adjust-hue(#253664, 118.4127), 35.8328), 34.3137);
```

This part is still a work in progress, but essentially, districts would be able to load their primary color and the palette would auto-populate in a consistent manner.

### Palette Codes

```scss
$sandy-brown: #ee9f58;
$sweet-corn: #f7e079;
$biscay: #253664;
$san-juan: #2e4965;
$black: #212121;
$dark-gray: #535353;
$white-lilac: #e9e9e9;
$mountain-mist: #8f8e95;
$slate-gray: #6b7f92;
$white: #eeeeee;
$curious-blue: #357ebd;
$solitaire: #fcf8e3;
$cool-blue: #008fff;
$picton-blue: #57aff5;
$carolina-blue: #9eb5d7;
$pastel-green: #64d682;
$valencia: #d6524b;
$black-haze: #f7f7f7;
$dark-pink: #ed4b7b;
```
