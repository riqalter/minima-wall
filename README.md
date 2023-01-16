# Minimalistic Wallpaper Collection

[![images](https://custom-icon-badges.demolab.com/github/directory-file-count/riqalter/minima-wall/images?label=images&logo=image)](https://github.com/riqalter/minima-wall/tree/main/images)

This is my collection of minimalistic, flat art, and colorful, digital nature wallpapers.

**Disclaimer:** I do not claim ownership of the wallpapers appearing in this repository. Most of these wallpapers were found on [Reddit](https://www.reddit.com/r/wallpaper/), DeviantArt, or Artstation. If you find images in this repository owned by you and are of limited use, please let me know and I will remove them.

## Wallpapers

To view a gallery of all 300+ wallpapers, [click here](https://tobe-online.com-placeholder/)!

## API

The website also includes a random wallpaper API, so you can request random wallpapers from the collection using a web request.

To use the API, simply make a request to:

```md
https://tobe-online.com-placeholder/?random
```

To get multiple random images at once, it is recommended to change the URL slightly to avoid caching. For example,

```md
https://tobe-online.com-placeholder/?random=1
https://tobe-online.com-placeholder/?random=2
https://tobe-online.com-placeholder/?random=3
```

This API can be used for setting daily wallpapers on a mobile device by combining it with an app such as IFTTT.

> **Note**
> By default, the API will fetch the image from GitHub and return it as content if it is smaller than 4.5MB.
> To force the API to redirect to the image on GitHub instead, add `&redirect=1` to the end of the URL.


