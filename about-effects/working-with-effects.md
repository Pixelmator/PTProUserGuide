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

# Working with effects

When working with effects, there are a couple of useful things to know that will let you maximize your results. For example, you can rearrange the order of effects applied, temporarily disable specific effects, or even reset all the effects applied to a particular layer.

{% embed url="https://d2hh90bli6ucxp.cloudfront.net/help/effects/split-comparison-working-with-effects-2.4.mp4" %}

## Turn effects on or off

You can apply effects to layers directly or add them as effects layers. Adding effects directly will automatically link them with the layer to which they are applied. This means that when editing, the changes applied to the layer will also affect the effect and vice versa. For instance, if you try painting on a layer that has some of the Distortion effects applied, the brush stroke have the same distortions as well.

1. Choose the Effects tool by doing one of the following:
   * Choose Effects <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1590058938000.png" alt="" data-size="line"> in the Tools sidebar.
   * Choose **Tools > Effects** from the Tools menu at the top of your screen.
   * Press the `F` key on your keyboard.
2. Select the layer or layers you would like to edit.
3. Turn the switch next to the effect you want on or off. If you don't see any effects, click **Add Effect** and choose an effect from the Effects browser.&#x20;

Keep in mind that the effects will show only on that layer or layer group to which they are applied. If you'd like to add effects to multiple layers in a composition, create an effect layer.

## Add effect layers

Effects layers work as individual elements you can add to a project and edit separately from the layer (or layers) to which they are applied. Just like applying effects to a single layer, creating effects layers let you work completely nondestructively. Effects layers can be moved freely up or down the layers list and will change the appearance of all other layers below them. Other than that, all the effects controls function the same way as they do when editing layers directly.

To add an effects layer, do any of the following:

* Choose **Insert > Effects** from the Insert menu at the top of your screen.
* Click the Add <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1604676890000.png" alt="" data-size="line"> at the top of the Effects pane.
* Click the Insert Layer <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1648724547000.png" alt="" data-size="line"> at the top of the Layers sidebar and choose Effects.
* Click the Add Layer <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1579274394000.png" alt="" data-size="line"> in the Toolbar and choose Effects.
* Press `Shift ⇧` + `Command ⌘` + `F` on your keyboard.

**Tip:** If you'd like to apply an effects layer to only one layer or layer group below it, you can do that using a clipping mask. See [Use clipping masks](https://www.pixelmator.com/support/guide/pixelmator-pro/1156) to learn more about working with clipping masks.

## Copy an effect from one layer to another

A quick way to apply the same effect to multiple layers is by using [effect presets](effect-presets.md). However, you can apply the same effect to multiple layers by copying it over.

1. Select the layer with the effect you’d like to copy.
2. To copy the effect, do one of the following:
   * Choose **Format > Effects > Copy Effects** from the Format menu at the top of your screen.
   * In the Layers sidebar, `Control ⌃` – click the layer from which you’d like to copy a effect and choose **Effects > Copy Effects**.
3. Select the layer to which you’d like to apply the copied effect.
4. To paste an effect, do one of the following:
   * Choose **Format > Effects > Paste Effects** from the Format menu at the top of your screen.
   * In the Layers sidebar, `Control ⌃` – click the layer to which you’d like to paste the effects and choose **Effects > Paste Effects**.

## Rearrange the order of effects

If you apply two or more effects to a single layer, you can rearrange the order in which they are combined. For example, if you apply a Gaussian blur effect and a Kaleidoscope effect, putting the Gaussian effect on top will mean your original layer is tiled first, then the result is blurred.

To rearrange effects, click and drag the effect up or down the list of effects.

Temporarily see the original layer without any effects

1. In the [Layers sidebar](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary), click to select the layer you'd like to see without any effect.
2. Click and hold the Show Original button at the bottom of the [Tool Options pane](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary), or press Control ⌃ + M on your keyboard.

**Tip:** If you're editing an effects layer, you can also click its visibility checkbox in the Layers sidebar to hide all effects.

## Turn on Split Comparison view

Using the Split Comparison view, you can see what an image looked like before and after you applied any effects to it. There are a few ways you can turn on the Split Comparison view:

* Option ⌥ – click the Show Original button at the bottom of the [Tool Options pane](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary).
* Press Control ⌃ + C on your keyboard.
* If you're using a trackpad, force click the canvas or two-finger tap the canvas and choose Split Comparison.
* Choose **Window > Customize Toolbar** and drag the Compare item to the toolbar.

## Temporarily turn off a single effect

1. In the [Layers sidebar](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary), click to select the layer in which you'd like to turn off an effect.
2. In the [Tool Options pane](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary), turn off the effect you want.

## Remove an effect

1. In the [Layers sidebar](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary), click to select the layer that has an unwanted effect.
2. Click ![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1604317638000.png) next to the effect you want to remove.

## Reset all effects applied to a layer

Do one of the following:

* In the [Layers sidebar](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary), Control ⌃ – click a layer and choose **Effects > Reset Effects**.
* Choose **Tools > Effects** and click the Reset Effects button at the bottom of the [Tool Options pane](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary).

## Flatten effects

Flattening all the effects applied to a layer can be useful when you’re happy with the way it looks and you’d like to resize the layer without the effect repeating beyond the edges of the layer (which happens with Tile effects, for example).

Do any of the following:

* In the [Layers sidebar](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary), Control ⌃ – click a layer and choose **Effects > Flatten Effects**.
* Choose **Format > Effects > Flatten Effects**.
* Option ⌥ – click the Reset button at the bottom of the [Tool Options pane](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary).

\