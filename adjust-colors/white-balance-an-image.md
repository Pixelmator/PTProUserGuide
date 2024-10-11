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

# White balance an image

Sometimes, after shooting a particular scene, you may want to make the entire image warmer (more yellow) or cooler (bluer). Or you might notice that an image looks too warm, too cool, or has a green or magenta tint that you’d like to remove. The White Balance adjustment lets you do just that — you can adjust the white balance manually, or automatically using the machine learning-powered ML adjustment. ML uses computer vision to recognize objects in the image (for example, people, trees, or a sky), and white balances it to remove any unnatural color tints.

You can white balance a single layer or, using a color adjustments layer, multiple layers in a composition.

## Adjust the white balance of the currently selected layer

* Choose **Format > Color Adjustments > White Balance** from the Format menu at the top of your screen.
* In the Tools sidebar, click the Color Adjustments <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1581000192000.png" alt="" data-size="line"> tool and turn on White Balance.
* Press `A` on your keyboard and turn on the White Balance adjustment.

## White balance multiple layers in a composition

* Choose **Insert > Color Adjustments** from the Insert menu at the top of your screen and turn on the White Balance adjustment in the Tool Options pane.
* Click <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1648724547000.png" alt="" data-size="line"> at the top of the Layers sidebar, choose Color Adjustments, and turn on the White Balance adjustment.
* Press `Shift ⇧` + `Command ⌘` + `A` on your keyboard, and turn on the White Balance adjustment.

:blue\_book: **Note:** If the adjustment isn't visible, you can turn it on from the Customize menu at the bottom of the Color Adjustments pane.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1655991133000.jpeg)

## Manually adjust color temperature and tint

1. Drag the Temperature slider to the left to make the image cooler, or to the right to make it warmer. Press and hold the `Option ⌥` key before dragging if you’d like to extend the range of the Temperature slider beyond 100%. You can also enter a percentage value from –200% to 200%.
2. Drag the Tint slider to the left to add a green tint (or neutralize a magenta tint) or drag the slider to the right to add a magenta tint (or neutralize a green tint). Press and hold the `Option ⌥` key before dragging if you’d like to extend the range of the Tint slider beyond 100%. You can also enter a percentage value from –200% to 200%.

## Automatically correct the white balance

Click ML in the Tool Options pane next to the White Balance adjustment

<div align="left">

<img src="../.gitbook/assets/White Balance.jpg" alt="" width="563">

</div>

## White balance an image by choosing a neutral gray area

Click the White Balance eyedropper and then click an area in your image that should be a neutral grey.

<div align="left">

<img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1655990975000.jpeg" alt="" width="563">

</div>

After doing this, you can manually fine-tune the automatic adjustments applied to your image by dragging the Temperature and Tint sliders.

## Show before and after or reset adjustments

_Show Original:_ Click the Show Original button or press `Control ⌃` + `M` on your keyboard to see what the image looks like without any color adjustments.

_Show Split Comparison:_ `Option ⌥` – click the Show Original button, press `Control ⌃` + `C` on your keyboard, or force-click the canvas.

To reset all Color Adjustments, click Reset at the bottom of the Color Adjustments pane.
