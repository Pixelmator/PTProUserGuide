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

# Use layer masks

A layer mask is like an additional sheet you can place over a layer or layer group to hide parts of it. Layer masks are nondestructive because even though the parts they hide are no longer shown, the original layer is fully preserved, and if you turn off or remove the mask, the full layer will reappear. You can also go back to make adjustments to layer masks after adding them.

## Add bitmap or vector masks

The quickest way to add a mask is by choosing an option from the special Mask <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1649061178000.png" alt="" data-size="line"> menu at the top of the layers sidebar. Alternatively, you can do any of the following:

### Add a bitmap layer mask

* With the Arrange tool selected, double-click an image layer while holding `Option ⌥.`
* With the Arrange tool selected, double-click a selection while holding `Shift⇧`.
* Choose **Format > Mask > Add Mask** or **Choose Image Mask** from the Format menu at the top of your screen.
* In the Layers sidebar, `Control ⌃` – click a layer or layer group and choose Add Mask. You can also `Option ⌥` – click Add Mask to add a mask and hide the layer.
* `Command ⌘`-drag any image, text, or image from Finder onto a layer to create a mask.

### Add a vector mask

* With the Arrange tool selected, double-click an image layer.
* With the Arrange tool selected, double-click a selection.
* Choose **Format > Mask > Mask with Shape** from the Format menu at the top of your screen.
* In the Layers sidebar, `Control ⌃` – click a layer, choose Mask with Shape, then select an option.
* `Command ⌘`-drag any shape from the Layers sidebar or directly from any Shape browser in Pixelmator Pro to mask a layer with a shape.

<details>

<summary>Edit and refine bitmap masks</summary>

**Edit using on-canvas controls**

Editing masks is easy with handy on-canvas controls that appear when you select a mask layer. If the controls are not visible, make sure the Arrange tool is selected.

1. Select the bitmap mask you want to edit.
2. Do any of the following:&#x20;
   * _Paint to hide or reveal additional areas:_ Use Paint and Erase brushes in the on-canvas controls at the bottom of the screen to hide or reveal the layer. When working on the mask, you can adjust the Brush Settings to control the brush size, softness, and opacity.
   * _Adjust the mask opacity:_ Click Mask Settings and drag the Opacity slider to control the overall transparency of the mask, including the unmasked areas of a layer.
   * _Adjust the mask density:_ Click Mask Settings and drag the Density slider to control the strength of the masking effect in the masked areas of a layer.
   * _Adjust the mask softness:_ Click Mask Settings and drag the Feather slider to control how much to soften the edges of the mask.
   * _Invert the mask:_ Click Invert Mask to make transparent areas opaque and vice versa. You can also press `Command ⌘` + `I` on your keyboard to invert a mask.

**Refine a mask**

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
     \
     Use the Refine Edge Brush to add or subtract only at the edges of the mask.\
     \
     Use the Quick Selection Brush to add or subtract from the mask as if using the Quick Selection tool.\
     \
     Use the Basic Brush to add or subtract from the mask as if painting with a basic brush.

**Edit a mask using the Paint tool**

When you place a layer mask over an image, it is completely white by default. The completely white parts of a mask are 100% transparent, meaning everything below the white areas is visible. If you paint over the mask with pure black, the areas you paint over are completely hidden. Pure white is 100% transparent, pure black is 0% transparent, and shades of grey range from 1% to 99% transparency — the darkest grey is 1% transparent, 50% grey is 50% transparent, and off-white is 99% transparent. \
\
This lets you edit masks — hide or reveal areas — by simply painting on the mask with black or white brushes. See [Paint tool](https://www.pixelmator.com/support/guide/pixelmator-pro/1038) to learn more.

:bulb: **Tip:** When editing masks using the Paint tool, you can use the keyboard shortcut `D` to reset the primary and secondary colors in Pixelmator Pro to black and white and `X` to switch between the primary and secondary colors.

</details>

<details>

<summary>Edit vector masks</summary>

Editing vector masks is easy with handy on-canvas controls that appear when you select a mask layer. If the controls are not visible, make sure the Arrange tool is selected.

1. Select the vector mask you want to edit.
2. Do any of the following:&#x20;
   * _Change the mask shape:_ To replace your current mask, use the Shape tool in the on-canvas controls to open the Shapes browser and select a shape.
   * _Change the mask fill type:_ Click Mask Settings, and in the Mask Fill Type menu, select whether you want your mask to be a solid color or a gradient. You can edit the gradient mask just as you edit gradients.
   * _Adjust the mask opacity:_ Click Mask Settings and drag the Opacity slider to control the overall transparency of the mask, including the unmasked areas of a layer.
   * _Adjust the mask density:_ Click Mask Settings and drag the Density slider to control the strength of the masking effect in the masked areas of a layer.
   * _Adjust the mask softness:_ Click Mask Settings and drag the Feather slider to control how much to soften the edges of the mask.
   * _Invert the mask:_ Click Invert Mask to make transparent areas opaque and vice versa. You can also press `Command ⌘` + `I` on your keyboard to invert a mask.

</details>

