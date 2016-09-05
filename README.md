# reddit-cfb-slack-emojis

A set of images that are at most 128 x 128 so they can be used as slack emojis. Sourced from [/r/cfb](https://www.reddit.com/r/cfb). 

## to regenerate

get images: 

```bash
wget -r https://flair.redditcfb.com/fullorig/
```

to convert images using [imagemagick](https://www.imagemagick.org/script/index.php)

```bash
for f in *.png; do convert -scale 128x128 $f $f; done
```
