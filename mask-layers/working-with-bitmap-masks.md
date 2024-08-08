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

# Working with bitmap masks

Bitmap masks are pixel-based layer masks used to control the visibility of different areas in an image. When created, the mask is fully white, making everything visible. Painting on the mask with black will hide parts of the image, while grey shades provide partial transparency. Painting with white reveals hidden areas again.

You can easily edit these masks using on-canvas controls, which appear when a mask layer is selected. If the controls are not visible, ensure the Arrange tool is active.

## Add a bitmap mask

* With the Arrange tool selected, double-click an image layer while holding `Option ⌥.`
* With the Arrange tool selected, double-click a selection while holding `Shift⇧`.
* Choose **Format > Mask > Add Mask** or **Choose Image Mask** from the Format menu at the top of your screen.
* In the Layers sidebar, `Control ⌃` – click a layer or layer group and choose Add Mask. You can also `Option ⌥` – click Add Mask to add a mask and hide the layer.
* `Command ⌘`-drag any image, text, or image from Finder onto a layer to create a mask.

## Edit a bitmap mask

1. Select the bitmap mask you want to edit.
2. Do any of the following:&#x20;
   * _Paint to hide or reveal additional areas:_ Use Paint and Erase brushes in the on-canvas controls at the bottom of the screen to hide or reveal the layer. When working on the mask, you can adjust the Brush Settings to control the brush size, softness, and opacity.
   * _Adjust the mask opacity:_ Click Mask Settings and drag the Opacity slider to control the overall transparency of the mask, including the unmasked areas of a layer.
   * _Adjust the mask density:_ Click Mask Settings and drag the Density slider to control the strength of the masking effect in the masked areas of a layer.
   * _Adjust the mask softness:_ Click Mask Settings and drag the Feather slider to control how much to soften the edges of the mask.
   * _Invert the mask:_ Click Invert Mask to make transparent areas opaque and vice versa. You can also press `Command ⌘` + `I` on your keyboard to invert a mask.

## Refine a bitmap mask

Once you've made some basic adjustments to your mask, you can further refine it using the Refine Mask tool.

1. Select the mask you want to refine.
2. To choose the Refine Mask tool, do one of the following:
   * Click More in the on-canvas mask controls and choose Refine Mask.
   * In the Layers sidebar, `Control ⌃` – click the layer mask, and choose Refine Mask.
   * Select the mask or the masked layer, then choose **Format > Mask > Refine Mask** from the Format menu at the top of your screen.
3. Refine your mask by adjusting the options in the Tool Options pane:
   * _Shape Roundness:_ Adjust how much to round the mask outline.&#x20;
   * _Edge Softness:_ Adjust how much to soften the edges of the mask outline. With softer edges, the masked area will blend in better with other parts of the image should you copy or edit it.
   * _Expand:_ Change the size of the mask.
   * _Mask Subject:_ Automatically create a mask for the subject in your image.
   * _Smart Refine:_ Use a machine learning-based algorithm to intelligently detect intricate details like hair or fur at the edges of the mask and automatically refine the outline.
   * _Invert Mask:_ Inverting a mask makes the opaque areas of the masked image transparent and vice versa.
   * _Add or subtract areas from the mask:_\
     Use the Refine Edge Brush to add or subtract only at the edges of the mask.\
     Use the Quick Selection Brush to add or subtract from the mask as if using the Quick Selection tool.\
     Use the Basic Brush to add or subtract from the mask as if painting with a basic brush.

## Edit a mask using the Paint tool

When you place a layer mask over an image, it is completely white by default. The completely white parts of a mask are 100% transparent, meaning everything below the white areas is visible. If you paint over the mask with pure black, the areas you paint over are completely hidden. Pure white is 100% transparent, pure black is 0% transparent, and shades of grey range from 1% to 99% transparency — the darkest grey is 1% transparent, 50% grey is 50% transparent, and off-white is 99% transparent. \
\
This lets you edit masks — hide or reveal areas — by simply painting on the mask with black or white brushes. See [Paint tool](../paint-and-erase/) to learn more.

:bulb: **Tip:** When editing masks using the Paint tool, you can use the keyboard shortcut `D` to reset the primary and secondary colors in Pixelmator Pro to black and white and `X` to switch between the primary and secondary colors.

## Replace a bitmap mask

You can change the content of a bitmap layer mask by replacing it with any other image on your Mac. You can also replace vector masks with other shapes from your Shapes library.

1. In the Layers sidebar, click to select a layer mask you want to replace.
2. Do any of the following:
   * Choose **Format > Mask > Replace Image Mask** from the Format menu at the top of your screen.
   * In the Layers sidebar `Control ⌃` – click the layer mask, and choose Mask > Replace Image Mask.
   * In the mask on-canvas controls, click More and choose Replace Image Mask.&#x20;
