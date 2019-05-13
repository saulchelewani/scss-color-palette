# SCSS Color Palette
A 54 shade color palette for branded designs. It uses hsl values to create 9 lighter or darker shades of your 
preferred 
`primary` 
color, `secondary` color, `amber`, `red`, `green` and `grey`/`neutral`

## How to use

* Update `$primary` and `$secondary` to your preferred hue values.
* Import `_colors.scss` to your base `scss` file: `@import "colors"`.
* In your `scss` file you can use `color: neutral($foreground)` or `background-color: spin($primary, $background)` etc.

## Available Color Variables

### Neutral/Grey Color Shades
Choose your shade by calling `neutral($shade)`
#### Available Neutral Shades
You can pass any of the following variables for neutral color shades <br />
`foreground`, `darkest`, `darker`, `dark`, `light`, `lighter`, `lightest`, `background`. <br />
#### Example
`background-color: neutral($light);` <br />
For base color, use `neutral()` without an argument


### Various Color Shades
Choose your color by spinning the hue wheel and selecting the shade of that color: `spin($baseColor, $shade)`
#### Available Base Colors
You can pass any of the following variables as `baseColor`:<br />
`primary`, `secondary`, `amber`, `green`, `red` <br />

#### Available Shades
You can pass any of the following variables for various color `shade`: <br />
`foreground`, `darkest`, `darker`, `dark`, `light`, `lighter`, `lightest`, `background`. <br />
#### Example
`color: spin($red, $darker);` <br />
For base color use `spin($red)` without the second argument.


