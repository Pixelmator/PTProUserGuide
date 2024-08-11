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

# Change the image size

You can change the size of images to reduce or enlarge them. The image size can be set using pixels or a print unit, such as inches or centimeters. However, print units on their own have no relationship to pixels because a pixel has no physical size. For this reason, there is an additional Resolution field that specifies how many pixels should be printed in an inch or centimeter.&#x20;

If you are working on an image for the web or one that will only be displayed on a screen, you should size and resize images using pixels (and you can ignore the Resolution setting completely). If you are working on an image that will be printed, you should use print units with an appropriate resolution.&#x20;

When resizing images, you can also choose from four image scaling algorithms, including the machine learning-powered Super Resolution.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1654695622000.jpeg)

## Change the pixel dimensions of an image

1. Do one of the following:
   * Choose **Image > Image Size** from the Image menu at the top of your screen.
   * Press `Option ⌥` + `Command ⌘` + `I` on your keyboard.
2. Choose pixels from the Unit pop-up menu.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1654695671000.jpeg)

3. Enter a new width and height for the image or use [text field math](pixelmator-pro-basics/use-text-field-math.md) to calculate it.\
   :bulb: **Tip:** If you’d like to resize the image without keeping its original proportions, deselect the _Scale proportionally_ checkbox.
4. Click OK to apply your changes or Cancel to cancel them.

:blue\_book: **Note:** When changing the pixel size of an image, the Resolution has absolutely no effect on the actual size or quality of the image. The standard number used is 72 or 300, but this is essentially placeholder text for any image sized in pixels. If you need to change the print size of an image, see the section below.

## Change the print dimensions of an image

1. Do one of the following:
   * Choose **Image > Image Size** from the Image menu at the top of your screen.
   * Press `Option ⌥` + `Command ⌘` + `I` on your keyboard.
2. Choose a print unit (inches, cm, mm, or points) from the Unit pop-up menu.
3.  Enter a new width and height for the image or use [text field math](pixelmator-pro-basics/use-text-field-math.md) to calculate it.

    :blue\_book: **Note:** If you’d like to resize the image without keeping its original proportions, deselect _Scale proportionally_.
4.  Enter a new resolution for the image.

    When you change the print dimensions of an image, you’re essentially changing its pixel dimensions indirectly by letting Pixelmator Pro calculate the size for you. The basic formula for this is Print Size x Resolution = Pixel Dimensions. So, if you have a 10x10 inch image at 300 PPI, its pixel size would be 3000x3000. _Note:_ If you’d like to change the print dimensions of an image without changing the quality of the image (or its pixel dimensions), deselect the _Resample_ checkbox. This way, changing the resolution will automatically change the print dimensions and vice versa, ensuring the pixel size of the image stays the same. Note that because you'll be changing the physical size of the image, pixels as measurement units will be grayed out.&#x20;

5\. Click OK to apply your changes.

:bulb: **Tip:** The standard resolution for high-quality prints is 300 pixels/inch (PPI), although a lower resolution is often used for larger posters and other media that is viewed from a distance where it would be difficult to see individual pixels. For web graphics and images, a resolution of 72 PPI is often used as the default, although this is essentially placeholder text as web images should always be sized in pixels.

## Choose a different image scaling algorithm

In Pixelmator Pro, you can resize images using one of four scaling algorithms: Bilinear, Lanczos, Nearest Neighbor, and Super Resolution.

To choose a scaling algorithm:

1. Do one of the following:
   * Choose **Image > Image Size** from the Image menu at the top of your screen.
   * Press `Option ⌥` + `Command ⌘` + `I` on your keyboard.
2. Select the algorithm:
   1. The _Bilinear_ algorithm is more or less the standard in image editing. It tries to naturally smooth edges (transitions between light and dark colors) by guessing the intermediate colors, so it's useful for photographic images. However, this can sometimes cause blurry images (especially when upscaling).
   2. The _Lanczos_ algorithm is designed to preserve small details when upscaling and downscaling, which is useful for things like graphics, though it's important to watch out for haloing issues.
   3. The _Nearest Neighbor_ algorithm is mostly used for pixel art, as it copies the color of the nearest neighboring pixels resulting in the classic blocky image look.
   4. _Super Resolution_ is a machine learning-powered scaling algorithm, trained to intelligently upscale images while preserving details that can often be lost when using traditional scaling. To learn more about Super Resolution and how we've built it, check out our [comprehensive blog post](https://www.pixelmator.com/blog/2019/12/17/all-about-the-new-ml-super-resolution-feature-in-pixelmator-pro/).

## Change the canvas size

Changing the canvas size of an image changes its overall size without changing the size of any of its contents. In short, the editable canvas of your image increases or decreases, but whatever was on the canvas doesn’t change. Increasing the canvas size adds additional space around your image, whereas decreasing the canvas size essentially crops the image. However, the cropped areas are not deleted, they are simply hidden beyond the edges of the canvas.

1. Do one of the following:
   * Choose **Image > Canvas Size** from the Image menu at the top of your screen.
   * Press `Option ⌥` + `Command ⌘` + `C` on your keyboard.
2. Choose a unit from the Unit pop-up menu.
3.  Enter a new canvas size for the image or use [text field math](pixelmator-pro-basics/use-text-field-math.md) to calculate it.

    Select the _Relative_ checkbox if you’d like to specify how much to add to or subtract from the current canvas instead of entering a specific canvas size.
4. Move the canvas box to choose where the original image should be placed on the new canvas.
5. Click OK to apply your changes.
