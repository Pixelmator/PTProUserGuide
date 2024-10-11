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

# Adjust the tonal curve of an image

The Curves adjustment is one of the most versatile color adjustments. You can use Curves for almost everything — adjusting the tones and contrast of an image, or creating artistic effects. Because of the different ways you can use Curves, it can often work as a substitute for other color adjustments such as Lightness, White Balance, or Channel Mixer.

The Curves adjustment works by selectively adjusting the tonal values of an image. The image tonality itself is represented by a diagonal line crossing a square graph.

<div align="left">

<img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1656337597000.png" alt="" height="331" width="341">

</div>

The dark values are on the left side of the graph and the light values on the right. You can add points to the tonal curve and drag the tonal curve up or down depending on whether you wish to darken, lighten, or change a particular value in an image. The shape of the diagonal line changes as you add and drag the points and often ends up looking like a curve which gave the adjustment its name.

## Adjust the tonal curve of an image

The Curves adjustment can be applied directly to a single layer or, using a color adjustments layer, to multiple layers in a composition.

### Edit the currently selected layer

* Choose **Format > Color Adjustments > Curves** from the Format menu at the top of your screen.
* In the Tools sidebar, click Color Adjustments <img src="../.gitbook/assets/Color-Adjustments.png" alt="" data-size="line"> and turn on the Curves adjustment.
* Press `A` on your keyboard and turn on the Curves adjustment.
* Press `Command ⌘` + `K` on your keyboard.

### Edit multiple layers in a composition

* Choose **Insert > Color Adjustments** from the Insert menu at the top of your screen and turn on the Curves adjustment in the Tool Options pane.
* Click Insert a layer <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1648724547000.png" alt="" data-size="line"> at the top of the Layers sidebar, choose Color Adjustments, and turn on the Curves adjustment.
* Press `Shift ⇧` + `Command ⌘` + `A` on your keyboard, and turn on the Curves adjustment.

:blue\_book: **Note:** If the adjustment isn't visible, you can turn it on from the Customize menu at the bottom of the Color Adjustments pane.

## Curves adjustment overview

The Curves adjustment consists of a few different sections:

<div align="left">

<img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1656337223000.png" alt="" width="375">

</div>

1. **Histogram.** Shows the distribution of highlights, shadows, or midtones to help adjust the curves accordingly.
2. **The Curves adjustment pop-up menu.** Click it to choose which channels to adjust.
3. **Black, gray, and white color pickers.** You can use these color pickers to automatically adjust the curves in different RGB channels.
4. **More menu.** Click it to apply Auto Contrast and Auto Color.
5. **White point.** You can drag this point to the left to add more of the pure white color to your image.
6. **Control point.** Click the curve to add new points. RGB images have 255 different values for each of the three channels, ranging from 0 (completely black) to 255 (completely white). Every new point you add to the tonal curve (and you can add up to 14 of them) will have its own assigned value. Drag the points off of the graph to remove them.
7. **Black point.** You can drag this point to the right to add more of the pure black color to your image.

## Adjust image highlights, midtones, and shadows

Adjust the different sections of the curve:

* To adjust the highlights, click the top section of the curve to add a new point. Drag the point up to brighten the highlights or down to darken them.
* To adjust the shadows, click the bottom section of the curve to add a new point. Drag the point up to brighten the shadows or down to darken them.
*   To adjust the midtones, click the middle section of the curve to add a new point. Drag the point up to brighten the midtones or down to darken them.

    You can remove points by dragging them off the Curves graph.

:bulb: **Tip:** A couple of the most common Curves adjustments are known as the S-curve and an inverted S-curve. The S-curve adds more contrast to the image, while the inverted S-curve does the exact opposite — reduces it. Extremely steep or very flat curves usually aren’t recommended unless they’re used for a specific artistic effect, such as posterizing. Otherwise, smooth curves usually give the best results.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1656338034000.png)

## Adjust individual RGB channels to change the color and tone of an image

When adjusting Red, Green, and Blue channels individually, dragging the curve points upward adds more of that color to an image, while dragging the points down boosts its complementary color instead. The complementary color pairs are cyan for red, magenta for green, and yellow for blue. So, for instance, for an image that has too much blue in the shadows, adding a point somewhere around the bottom of the curve and dragging it down will bring in more yellow to neutralize the blue. This also works vice versa — you can neutralize a yellow image by dragging the blue channel curve up.

1. Click the Curves pop-up menu and choose Red, Green, or Blue.
2. Click the tonal curve to add a new point and drag it to adjust the colors.

## Automatically enhance image contrast

The Auto Contrast adjustment automatically adjusts the luminance of an image:

* Click the More <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1605111967000.png" alt="" data-size="line"> menu and choose Auto Contrast.

<div align="left">

<img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1656337719000.png" alt="" height="331" width="300.5">

</div>

## Automatically enhance image colors

The Auto Color adjustment automatically adjusts the Red, Green, and Blue channels of an image:

* Click the More <img src="../.gitbook/assets/More.png" alt="" data-size="line"> menu and choose Auto Color.

<div align="left">

<img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1656337773000.png" alt="" height="331" width="301">

</div>

## Automatically enhance an image by setting black, gray, and white points

In the top-right corner of the Curves adjustment, you’ll notice three color pickers:

* _Set the black point:_ Use the color picker on the left to pick an area in an image that should be pure black. The curves in the Red, Green, and Blue channels are automatically adjusted.
* _Set the grey point:_ Use the middle color picker to pick an area in an image that should be midtoned.
* _Set the white point:_ Use the color picker on the right to pick an area in an image that should be pure white.

## Show before and after or reset adjustments

_Show Original:_ Click the Show Original button or press `Control ⌃` + `M` on your keyboard to see what the image looks like without any color adjustments.

_Show Split Comparison:_ `Option ⌥` – click the Show Original button, press `Control ⌃` + `C` on your keyboard, or force-click the canvas.

To reset all Color Adjustments, click Reset at the bottom of the Color Adjustments pane.
