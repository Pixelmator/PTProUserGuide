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

# Working with vector masks

Vector masks in Pixelmator Pro allow you to mask layers into specific shapes. They instantly hide or reveal parts of layers based on the shape boundaries, making the areas inside visible and the outside hidden. To apply a vector mask, you can select a shape from the Mask menu, create one with Pen tools, or choose from various shapes in the Shape browser.

## Add a vector mask

* Open the Mask <img src="../.gitbook/assets/Mask.png" alt="" data-size="line"> menu at the top of the layers sidebar and choose a shape, or choose Pen or Freeform Pen tools to draw a mask from scratch.
* With the Arrange tool selected, double-click an image layer.
* With the Arrange tool selected, double-click a selection.
* Choose **Format > Mask > Mask with Shape** from the Format menu at the top of your screen.
* In the Layers sidebar, `Control ⌃` – click a layer, choose Mask with Shape, then select an option.
* `Command ⌘`-drag any shape from the Layers sidebar or directly from any Shape browser in Pixelmator Pro to mask a layer with a shape.

## Edit a vector mask

Editing vector masks is easy with handy on-canvas controls that appear when you select a mask layer. If the controls are not visible, make sure the Arrange tool is selected.

1. Select the vector mask you want to edit.
2. Do any of the following:&#x20;
   * _Change the mask shape:_ To replace your current mask, use the Shape tool in the on-canvas controls to open the Shapes browser and select a shape.
   * _Change the mask fill type:_ Click Mask Settings, and in the Mask Fill Type menu, select whether you want your mask to be a solid color or a gradient. You can edit the gradient mask just as you edit gradients.
   * _Adjust the mask opacity:_ Click Mask Settings and drag the Opacity slider to control the overall transparency of the mask, including the unmasked areas of a layer.
   * _Adjust the mask density:_ Click Mask Settings and drag the Density slider to control the strength of the masking effect in the masked areas of a layer.
   * _Adjust the mask softness:_ Click Mask Settings and drag the Feather slider to control how much to soften the edges of the mask.
   * _Invert the mask:_ Click Invert Mask to make transparent areas opaque and vice versa. You can also press `Command ⌘` + `I` on your keyboard to invert a mask.

## **Refine a vector mask**

Vector masks are fully editable and allow you to adjust individual points just like editing regular shapes. They also offer resolution-independent scaling, making them ideal for high-quality designs of any size, such as web or print graphics.

See the section [Draw shapes and vector graphics](../draw-shapes-and-vector-graphics/) to learn more about editing shapes and managing your shapes library.

:blue\_book: **Note:** You can refine vector masks using the Refine Mask tool just like you [refine bitmap masks](working-with-bitmap-masks.md#refine-a-bitmap-mask), but this process converts them to bitmap.

## **Replace a vector mask**

You can change the content of a bitmap layer mask by replacing it with any other image on your Mac. You can also replace vector masks with other shapes from your Shapes library.

1. In the Layers sidebar, click to select the vector mask you want to replace.
2. Do any of the following:
   * In the on-canvas controls, click to open the Shape browser and select a shape.
   * In the mask on-canvas controls, click More and choose Replace Shape Mask.
   * Choose **Format > Mask > Replace Shape Mask** from the Format menu at the top of your screen.
   * In the Layers sidebar `Control ⌃` – click the layer mask, and choose Mask > Replace Shape Mask.
