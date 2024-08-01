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

# Remove color from an image

Use the Remove Color adjustment to remove any color or an entire color range from an image or video. Remove Color uses a texture-aware algorithm for removing colors, so the transitions between opaque and transparent areas are especially smooth, even in images with visible compression artifacts.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1677227475000.jpeg)

***

### Remove color from an image or video

1.  You can remove color from a single layer or, using a color adjustments layer, multiple layers in a composition.

    To remove color from the currently selected layer, do one of the following:

    * Choose **Format > Color Adjustments > Remove Color** (from the Format menu at the top of your screen).
    * In the [Tools sidebar](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary), click ![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1581000192000.png) and turn on the Remove Color adjustment.
    * Press A on your keyboard and turn on the Remove Color adjustment.

To remove color from multiple layers in a composition using a [color adjustments layer](https://www.pixelmator.com/support/guide/pixelmator-pro/1343) (all layers below this layer will be affected):

* Choose **Insert > Color Adjustments** (from the Insert menu at the top of your screen) and turn on the Replace Color adjustment in the [Tool Options pane](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary).
* Click ![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1648724547000.png) at the top of the [Layers sidebar](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary), choose Color Adjustments, and turn on the Remove Color adjustment.
* Press Shift ⇧ + Command ⌘ + A on your keyboard, and turn on the Remove Color adjustment.

_Note:_ If the adjustment isn't visible, you can turn it on from the Customize menu at the bottom of the Color Adjustments pane.

2\. By default, the color to be removed is set to chroma key green. To change it to a different color, in the Tool Options pane, click the color well and choose a specific color you want to remove or pick a color directly from the image using the eyedropper.

3\. Drag the Color Range slider to adjust how many of the colors similar to your selected color should be removed.

4\. Drag the Luminance Range slider to adjust how much color is removed based on the lightness of the tones in the selected color range.

5\. Drag the Intensity slider to adjust the transparency of the selected color range.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1677231596000.png)

_Show Original:_ Click the Show Original button or press Control ⌃ + M on your keyboard to see what the image looks like without any color adjustments.

_Show Split Comparison:_ Option ⌥ – click the Show Original button, press Control ⌃ + C on your keyboard, or force click the canvas.

To reset all Color Adjustments, click Reset at the bottom of the Color Adjustments pane.
