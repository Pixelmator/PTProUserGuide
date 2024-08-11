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

# Apply other effects

The effects in this category allow you to change the perspective of a layer, mask your selected layer to alpha, or apply a high pass filter to your image.

## Apply Other effects

Effects can be applied directly to a single layer or, using an effects layer, to multiple layers in a composition.

1. Select the layer or layers you want to edit.
2.  Do any of the following:\
    \
    Apply effects to a currently selected layer:

    * Click Effects <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1590058938000.png" alt="" data-size="line"> in the Tools sidebar, then click Add Effect and select an effect from the Other collection.
    * Choose **Format > Effects > Other** and choose an effect.
    * Press `F` on your keyboard, click Add Effect, and select an effect from the Other collection.

    Apply effects to multiple layers:

    * Choose **Insert > Effects** from the Insert menu at the top of your screen, click Add Effect, and select an effect from the Other collection.
    * Click Insert a layer <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1648724547000.png" alt="" data-size="line"> at the top of the Layers sidebar, choose Effects, click Add Effect, and select an effect from the Other collection.
    * Press `Shift ⇧` + `Command ⌘` + `F` on your keyboard, click Add Effect, and select an effect from the Other collection.

### Perspective Transform effect

The Perspective Transform effect lets you nondestructively transform an image by dragging the handles of the effect rope at the top left, top right, bottom left, or bottom right corner of the image.

### Mask to Alpha effect

The Mask to Alpha effect turns an image black and white and adds transparency to all black and grey areas of the image.

### High Pass effect

The High Pass effect can be considered the opposite of the Gaussian blur effect. Instead of blending out the edges and details in an image, High Pass accentuates them, keeping any flat areas of an image solid gray. The High Pass effect is often used for portrait retouching and combined together with the Overlay blend mode.

Customize the effect:

* Drag the _Radius_ slider to the right to highlight more pixels surrounding the edges and details in an image, or drag it to the left to include less of the surrounding pixels. You can also enter a value from 0.0 px to 100.0 px.
* Drag the _Opacity_ slider to the right to increase the contrast of the effect, or to the left to decrease it. You can also enter a value from 0% to 100%.
* Click the Blend Mode pop-up menu — the words "Opacity (Normal)" — and choose a blend mode.

:bulb: **Tip:** The High Pass effect is often used in combination with contrast blend modes (such as Overlay, Hard Light, etc.) to create different image sharpening effects.

### Low Pass effect

The Low Pass effect lets you nondestructively smooth out and remove noise from images. The Low Pass effect is often used in portrait retouching for smoothing out uneven skin textures and colors.

Customize the effect:

* Drag the _Radius_ slider to the right to smooth out finer textures in an image, or drag it to the left to keep more details. You can also enter a value from 0.0 px to 100.0 px.
* Drag the _Opacity_ slider to the right to increase the intensity of the effect, or to the left to decrease it. You can also enter a value from 0% to 100%.
* Click the Blend Mode pop-up menu — the words "Opacity (Normal)" — and choose a blend mode.

:bulb: **Tip:** The Low Pass effect is often used in combination with layer blend modes to create different smoothing effects.

### Frequency Separation effect

Frequency Separation combines Low Pass and High Pass effects and lets you adjust fine details and overall tones in images separately.

Customize the effect:

* Drag the _High Pass_ slider to the right to highlight more pixels surrounding the edges and details in an image, or drag it to the left to include less of the surrounding pixels. You can also enter a value from 0.0 px to 100.0 px.
* Drag the _Low Pass_ slider to smooth out finer textures in an image, or drag it to the left to keep more details. You can also enter a value from 0.0 px to 100.0 px.
* Drag the _Opacity_ slider to the right to increase the intensity of the effect, or to the left to decrease it. You can also enter a value from 0% to 100%.
* Click the Blend Mode pop-up menu — the words "Opacity (Normal)" — and choose a blend mode.

## Show before and after or reset effects

_Show Original:_ Click the Show Original button or press `Control ⌃` + `M` on your keyboard to see what the image looks like without any effects.

_Show Split Comparison:_ `Option ⌥` – click the Show Original button, press `Control ⌃` + `C` on your keyboard, or force-click the canvas.

To reset all effects, click Reset at the bottom of the Tool Options pane.
