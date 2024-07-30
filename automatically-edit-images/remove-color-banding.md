---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Remove color banding

Color banding is one of the most common image artifact. It typically occurs in low-quality images, images that have been repeatedly exported using lossy image formats like JPEG, or 8-bit images that can physically store a limited number of colors.

These artifacts are mostly visible wherever there is a gradual transition between shades of the same color. For instance, in photos of the sky. Instead of smoothly shifting between shades, colors jump abruptly from one to the next, forming distinct bands of color.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1675172828000.jpeg)

You can easily remove posterization and compression artifacts from images using the machine learning-powered Deband feature, which improves images with just a click.

***

### Deband an image

Do any of the following:

1. Click **Format > Deband** from the Format menu at the top of your screen.
2. Press `Shift ⇧` + `Control ⌃` + `B` on your keyboard.

{% hint style="info" %}
For best results when debanding, [change the color depth of an image](https://www.pixelmator.com/support/guide/pixelmator-pro/1028) to 16 bits/Channel.
{% endhint %}
