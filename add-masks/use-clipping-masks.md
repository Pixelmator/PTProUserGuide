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

# Use clipping masks

A clipping mask is a type of layer that clips two or more layers together, forming a group of layers called a _clipping set_. In a clipping set, the bottommost layer (also called the base layer) sets the boundaries for the entire group. Any parts of the upper layers that go beyond the edges of the bottom layer are hidden or, in other words, masked.

## Add a clipping mask

1. Select a layer or layer group you'll be using as a base layer and move it below the layer or layer group that you'll be clipping to.
2. Do one of the following:
   * In the Layers sidebar, `Control ⌃` – click the layer or layer group you'd like to mask and select Create Clipping Mask.
   * Choose **Format > Mask > Create Clipping Mask** from the Format menu at the top of your screen.
   * Press and hold the `Option ⌥` key and click between the layers you want to become a clipping set.
   * Press `Option ⌥` + `Command ⌘` + `G` on your keyboard.

![](../.gitbook/assets/Pixelmator-Pro\_Add-a-clipping-mask.png)

## Release a clipping mask

Do one of the following:

* `Control ⌃` – click the layer or layer group that has the clipping mask applied and select Release Clipping Mask.
* Choose **Format > Mask > Release Clipping Mask** from the Format menu at the top of the screen.
* Press and hold the `Option ⌥` key and click between the layers you want to unlink.
* Press `Option ⌥` + `Command ⌘` + `G` on your keyboard.
