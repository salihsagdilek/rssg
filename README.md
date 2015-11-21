# Responsive ScreenShot Grabber
Captures the full height document even if it's not showing on the screen or captures with the provided range of screen sizes.

A basic example for taking a screen shot using phantomjs which is sampled for https://nodejs-dersleri.github.io/
## Requirements
Phantomjs

##usage

```
    phantomjs rssg.js {url} [output format] [clipping]
```
### example

```

    phantomjs rssg.js https://github.com/
    phantomjs rssg.js https://github.com/ pdf
    phantomjs rssg.js https://github.com/ true
    phantomjs rssg.js https://github.com/ png true
```