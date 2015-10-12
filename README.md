可以导出android不同分辨率的图片。

# ![Tools](https://github.com/redwarp/9-Patch-Resizer/blob/develop/res/img/icon_32.png) 9-Patch-Resizer

A resizer tool to automaticaly resize png files and 9 patches in several densities (previously hosted on https://code.google.com/p/9patch-resizer/)

[![Build Status](https://travis-ci.org/redwarp/9-Patch-Resizer.svg?branch=develop)](https://travis-ci.org/redwarp/9-Patch-Resizer)

## Download

To get the latest build (.jar or .exe file), check the release page on the github project: https://github.com/redwarp/9-Patch-Resizer/releases

The .exe file is just a wrapper around the executable .jar file, use it if you don't feel comfortable with a java archive ^_^

## What is it exactly?

Let's face it : juggling with densities for Android is a bit of a pain, especially when dealing with 9 patch png.

And then comes this tool, that takes a xhdpi PNG file, or 9.png file, and generates ldpi, mdpi and hdpi png files automatically.

As simple as drag and drop can get.

And here is the [changelog](https://github.com/redwarp/9-Patch-Resizer/wiki/Changelog)

Current version : *1.4.2*

You're using 9patch resizer for your apps ? Don't hesitate and leave me a message!

## Links

 * Images and stuff found on http://www.clker.com/ (The online royalty free public domain clip art)
 * Images are downsized using an optimized incremental scaling algorithm proposed by Chris Campbell (whoever that is) - http://today.java.net/pub/a/today/2007/04/03/perils-of-image-getscaledinstance.html

## Roadmap

- [ ] A proper "Settings" panel, to handle issues such as jpeg compression, etc etc...
- [ ] A few optimisations
- [x] Command line support
- [x] Options to set the input density (if people wan't to downsize from hdpi and not from xdpi for instance)
- [x] Proper JPG support

## Contributors

 * redwarp
 * Jean-Baptiste LAB - Made the app working in command line

Join us, and together, we can rule the galaxy as coders and...

## Notable forks

 * Soymonitus did a fork that also handles iOS resources, might come in handy for some people: https://github.com/soymonitus/9-Patch-Resizer

## Anyway...

If for some weird reasons, some of your PNG files aren't resized properly, don't hesitate to send them to me, so that I can investigate !

I hope it'll prove as useful to you as it is useful to me. If you like it, and have too much cash in you hands, don't hesitate to donate. I will probably use it on beers though, so you should probably not bother, if you care for my health.

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=UCXCHNNSUP8G4&lc=US&item_name=Elder%20Sign&item_number=Resizer&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif"/></a>
