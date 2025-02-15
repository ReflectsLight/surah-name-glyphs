<p align="center">
الْحَمْدُ لِلَّهِ رَبِّ الْعَالَمِينَ
</p>

## About

A collection of all the names of chapters in the Holy Qur'an in SVG format.
This was created to help designers and developers who're working on Muslim
apps that need to show names of Surahs. The SVGs were all part of an SVG font.
I had to use the IcoMoon app to convert the glyphs in the font to these files
you're seeing here. I hope it helps :)

## Layout

* [svg/](svg/) contains one SVG file per surah <br>
  Each SVG file has been extracted from an SVG font
  
* [png/512x512/](png/512x512/) contains one PNG file per surah <br>
  The 512x512 images are suitable for (but not limited to) [OpenGraph](https://ogp.me/) previews <br>

* [png/1500x500/](png/1500x500/) contains one PNG file per surah <br>
  The 1500x500 images are suitable for (but not limited to) [Mastodon](https://mastodon.social) profile banners <br>
  
* [bin/build-png](bin/build-png) is a shell script that's responsible
  for the generation of PNG images. <br>
  The PNG images are generated from the images found in the [svg/](svg/) directory

## Credit

Credit and thanks to [@gyenabubakar](https://github.com/gyenabubakar). Gyen is
the original author who extracted the glyphs from an SVG font. May Allah bless him.
This repository is focused on adapting the glyphs to be suitable for the
https://al-quran.reflectslight.io website.

## Sources

* [github.com/@ReflectsLight](https://github.com/ReflectsLight/surah-name-glyphs)
* [gitlab.com/@ReflectsLight](https://gitlab.com/ReflectsLight/surah-name-glyphs)
* [codeberg.org/@ReflectsLight](https://codeberg.org/ReflectsLight/surah-name-glyphs)
* [brew.bsd.cafe/@ReflectsLight](https://brew.bsd.cafe/ReflectsLight/surah-name-glyphs)

## License

Copyright remains with the original authors.
