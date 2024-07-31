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

The quickest way to add a mask is by choosing an option from the special Mask <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1649061178000.png" alt="" data-size="line"> menu at the top of the layers sidebar.\
\
Alternatively, you can do any of the following:

#### Add a bitmap layer mask

* With the Arrange tool selected, double-click an image layer while holding `Option ⌥.`
* With the Arrange tool selected, double-click a selection while holding `Shift⇧`.
* Choose **Format > Mask > Add Mask** or **Choose Image Mask** from the Format menu at the top of your screen.
* In the Layers sidebar, `Control ⌃` – click a layer or layer group and choose Add Mask. You can also `Option ⌥` – click Add Mask to add a mask and hide the layer.
* `Command ⌘`-drag any image, text, or image from Finder onto a layer to create a mask.

#### Add a vector mask

* &#x20;With the Arrange tool selected, double-click an image layer.
* With the Arrange tool selected, double-click a selection.
* Choose **Format > Mask > Mask with Shape** from the Format menu at the top of your screen.
* In the Layers sidebar, `Control ⌃` – click a layer, choose Mask with Shape, then select an option.
* `Command ⌘`-drag any shape from the Layers sidebar or directly from any Shape browser in Pixelmator Pro to mask a layer with a shape.

## Edit a layer mask

When you place a layer mask over an image, it is completely white by default. The completely white parts of a mask are 100% transparent, meaning everything below the white areas is visible. If you paint over the mask with pure black, the areas you paint over are completely hidden. Pure white is 100% transparent, pure black is 0% transparent, and shades of grey range from 1% to 99% transparency — the darkest grey is 1% transparent, 50% grey is 50% transparent, and off-white is 99% transparent.

1. To edit a layer mask, you'll first need to select it. Do one of the following:
   * In the [Layers sidebar](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary) select or enable the mask layer. You'll recognize mask layers from the <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1649061178000.png" alt="" data-size="line"> icon next to them. If the mask layer is subtracted, click the Mask button to reveal it.
   * Select the masked layer and choose **Format > Mask > Edit Mask** from the Format menu at the top of your screen.
2. Select the [Paint tool](https://www.pixelmator.com/support/guide/pixelmator-pro/1038) and paint on the mask with black or white brushes to edit it.



