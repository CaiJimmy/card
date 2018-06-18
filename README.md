# Card

![Card](https://i.imgur.com/XySeu3b.png)

A lightweight Material Design home page.

> [Demo](https://card-homepage.netlify.com/)

## Usage

### Add more links

I tried to make the homepage the simpliest possible, so I only added a few SVG icons from [IcoMoon](https://icomoon.io/). 

If you want to add more icon, go to IcoMoon and follow the next steps:

1. Pick icons
2. Go to "download" section
3. Below each icon, there's a "Get Code" button, click it
4. Copy "*Symbol Definition(s)*", and past it to **line 139** of `index.html`

To add more links, use the following HTML structure, and put it  before `</footer>` tag:

```HTML
<a href="LINK" target="_blank" style="background: #fff">
    <!-- INSERT "HTML (SVG <use>) from IcoMoon here" -->
    <span>Flickr</span>
</a>
```

> Replace `#fff` with the brand color. You can get help in [brand-colors](http://brand-colors.com/)

### Avatar / Card Image

Avatar can be changed in line 50 of `index.html`, and card image in line 47.
