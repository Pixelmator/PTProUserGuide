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

# Convert layers into pixels

In Pixelmator Pro, you can use both raster and vector layers. To convert a layer to a pixel-based format, try one of the following:

* In the Layers sidebar, `Control ⌃` – click a layer and choose Convert into Pixels.
* Select a layer, then choose **Format > Convert into Pixels** from the Format menu at the top of your screen.

:bulb: **Tip:** You can also rasterize regular image layers to merge any color adjustments, effects, or styles applied to them.

***

## What is the difference between pixel and vector layers?

Vector layers include shapes, text, and lines you can draw using the Pen tools. Each of these vector objects can be used to create vector graphics, including digital drawings, illustrations, logos, layouts, and more. A raster layer is any other type of layer that consists of pixels — images, masks, paintings, and photos — so when you paint or edit images, you're working with raster layers.

### Raster layers

A raster layer (or bitmap) is made up of _pixels_ which are, essentially, points of color placed within a rectangular grid. When looking at raster images up close, you can see these individual points but at a certain distance, they begin to form meaningful images.

The number of pixels in an image is always set, making raster layers resolution-dependent. When upscaling, pixel layers can lose detail, become blurry or pixelated as the pixels are being stretched. A good rule of thumb for creating new images is to start with larger dimensions. The more pixels there are in one inch of an image — the higher its resolution. You can always scale the image down later if you need it.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1655726218000.jpeg)

:bulb: **Tip:** The machine learning-powered [Super Resolution](../automatically-edit-images/automatically-increase-image-resolution.md) scaling algorithm in Pixelmator Pro can help compensate for the potential quality loss when upscaling, as it uses an extremely intelligent, content-aware machine learning-enhanced algorithm.

It's also possible to vectorize raster layers although the process is not as simple as rasterizing vector shapes and the results can often look quite different compared to the original image. One method is to manually trace objects using the Pen tools. Or, you can also use the selection tools to make a selection of an object and [convert it into a shape](../make-selections/convert-selections-into-shapes.md).

### Vector layers

The main building block of a vector object is a _path_. A path is a curved or straight line that connects two points. Paths can be open or closed and can consist of virtually an unlimited number of points but never less than two. You can also add, move, or delete points from a vector path to transform it however you like.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1655726202000.jpeg)

:blue\_book: **Note:** The text layers have their own, dedicated formatting tools. To edit individual vector paths of each character, you'd need to [convert text into a shape](../use-the-type-tool/convert-text-into-a-shape-or-pixel-layer.md).

Vectors are resolution-independent, meaning they can be scaled up or down without losing quality.

Tools that change the pixel structure of an image such as brushes, Repair, and Clone tools, and retouching tools, cannot be used on vector layers unless they are converted into pixels or, in other words, _rasterized_.
