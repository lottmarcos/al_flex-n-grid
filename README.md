# SkateApp | Front End project created in an [Alura](https://www.alura.com.br/) class.


## Style Guide

All ofthe stylization that was used in the project.

[Project at Figma.](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)

### Fonts

```html
Open Sans:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap">
```

### Colors

body: `#1D232A`

header: `#1D232A`

mobile header: `#15191C`

lateral menu: `#15191C`

card: `#2C343A`

font: `#FFFFFF`

alternative font: `#95999C`

links: `#0480DC`

button: `#0480DC`

shadow: `0px 4px 4px rgba(0, 0, 0, 0.16)`

### Icons

They are inside the `icons.ttf` font file. To use, first import the font into the project using `@font-face` and then use the code below to display the icon.

```css
@font-face {
    font-family: 'icones';
    src: url(../font/icones.ttf);
}
```

> Be careful with the file `icones.ttf`'s route. 

Shirts = `\e900`

Shopping Cart = `\e901`

Home = `\e902`

Crew = `\e903`

Menu = `\e904`

Coins = `\e905`

Notifications = `\e906`

Spot = `\e908`

Spots = `\e909`

Paintings = `\e90a`

Play = `\e90b`

Clock = `\e90c`

Down-Arrow = `\e90d`

Videos = `\e90e`

Views Count = `\e90f`

## Spacing

Button padding: `8px`

Element's margin: `16px/8px`

Spacing between the recents card title and its items: `24px`

## Size

Mobile sceen size: `360px`

Desktop screen size: `1440px`

Max width of the main content: `1120px`

Max width of any card in a Desktop: `256px`

Min height of a card: `320px`
