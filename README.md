# JDWI - Jelle Dekkers' Weather Icons

![Preview of JDWI](/Preview.jpg)

JDWI - Jelle Dekkers' Weather Icons - is a set of weather icons designed to complement Google's Material Design icons as well as possible. I was looking for decent icons for my weather skins, but I couldn't find any. So, I decided to do it myself.

These icons were created in Illustrator CC 2020 and converted to an icon font using IcoMoon. The font names are `JDWI`, `JDWI-MISC`, `JWDI-MOON` or `JDWI-WIND`, depending on the icon package. The ligatures for the icons are the same as the names of the svg files. For example, `waxing-crescent.svg` has the ligature `waxing-crescent`. The font name and ligatures are case sensitive. I do have to add a note, which is that the JDWI-COLR icons are NOT included in the icon font. This due to IcoMoon not accepting anything other than monochrome icons. Instead, I have included PNGs for those icons.

## How to use these in Rainmeter
```
[WeatherIcon]
Meter=String

Text=rain-night

FontFace=JDWI
FontSize=(24*0.75)
AntiAlias=1
```

Define other options as you see fit. Please use multiples of 24px for the FontSize, W and H options (but leave the `*0.75` in the FontSize) for the crispiest results.

## Credits
* [Albie Patacsil](https://unsplash.com/photos/NhAkd78UPiQ), [Adam Przeniewski](https://unsplash.com/photos/SnBtwfljShg), [NASA](https://unsplash.com/photos/U2uKrI4lci8), [Richard Horne](https://unsplash.com/photos/5UUlbAf4DLw) and [Lisa Therese](https://unsplash.com/photos/EVkncXSIi98) for the preview backgrounds.
* [Erik Flowers](https://erikflowers.github.io/weather-icons/) and [Google](https://fonts.google.com/icons?selected=Material+Icons) for inspiration.