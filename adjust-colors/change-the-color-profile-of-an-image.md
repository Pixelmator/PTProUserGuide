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

# Change the color profile of an image

Pixelmator Pro color manages your images automatically, but if you ever need to change the color profile, you can choose from any RGB profiles available on your Mac.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1652775858000.jpeg)

:blue\_book: **Note:** Pixelmator Pro can use any RGB color profile available on your Mac, so to use a profile, you first need to install it on macOS. This can be done by placing the color profile in the ColorSync Profiles folder of the macOS System library (/Library/ColorSync/Profiles).

## Assign a new color profile to an image

Assigning a new color profile to an image does not modify the individual color values in the image and the existing color values are displayed in the new color space. Assigning a new color profile will almost always change the look of the image, but because the color values are the same, assigning the original color profile will return the original look of the image. For that reason, this is a nondestructive action.

1. Do one of the following:
   * Click More <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1605162881000.png" alt="" data-size="line"> in the Pixelmator Pro toolbar and choose Color Profile.
   * Choose **Image > Color Profile** from the Image menu at the top of your screen.
   * Press `Shift ⇧` + `Command ⌘` + `K` on your keyboard.
2. Choose a new color profile from the Advanced pop-up menu.
3.  Select Assign Profile.

    If that option isn’t visible, click Show Details.
4. Click OK to apply your changes.

## Match the image to a new color profile

Matching the image to a new color profile modifies the individual color values in the image so that colors keep their current look as much as possible in the new color space. Matching to a new color profile may change the look of the colors in the image only slightly or not at all, but, because the color values are modified, matching to the original color profile would not return the original colors of the image. For that reason, this is a destructive action.

1. Do one of the following:
   * Click More <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1605162881000.png" alt="" data-size="line"> in the Pixelmator Pro toolbar and choose Color Profile.
   * Choose **Image > Color Profile** from the Image menu at the top of your screen.
   * Press `Shift ⇧` + `Command ⌘` + `K` on your keyboard.
2. Choose a new color profile from the Advanced pop-up menu.
3.  Select Match to Profile.

    If that option isn’t visible, click Show Details.
4. Click OK to apply your changes.
