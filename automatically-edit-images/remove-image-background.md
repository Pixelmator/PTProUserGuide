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

# Remove image background

The Remove Background tool automatically removes the background from various types of layers and layer groups. The AI-powered object detection algorithm lets you quickly process images with solid-color backgrounds (such as green screen and product photos) and isolate objects placed in busier settings. Because background removal is such a fundamental part of image editing, you'll always find the Remove Background tool within easy reach when working on your projects.

***

### Remove background from a layer or layer group

Do any of the following:

* Click the Remove Background button in the toolbar. If it's not visible by default, you can add it in the Customize Toolbar menu. Choose **Window > Customize Toolbar** to open the menu, then drag the Remove Background item to the toolbar.\
  \
  :blue\_book: **Note:** In case there are multiple subjects in your image, you can use any of the [selection tools](../make-selections/) to mark only the ones you'd like to keep. The background removal algorithm may still remove areas within your selection if these are not identified as subjects.
* Choose **Edit > Remove Background** from the Edit menu at the top of your screen.
* Press `Shift ⇧` + `Backspace ⌫` on your keyboard.
* While pressing and holding the `Command ⌘` key, drag and drop an image from your Mac or the web to the Layers sidebar.
* `Control ⌃` – click a layer or a layer group in the Layers sidebar and choose Remove Background.\
  \
  :bulb: **Tip:** When removing the background from a layer group, Pixelmator Pro creates a layer mask for that layer group. To delete the background completely, the Remove Background action would have to be performed on each layer within the group individually.
* Choose **Tools > Smart Erase** from the Tools menu at the top of the screen and click Remove Background.

***

If you'd like to hide the background instead of removing it completely, hold down the `Option ⌥` key when clicking Remove Background in the menu. This will mask the background instead of deleting it and you'll be able to [edit the mask](../working-with-layers/use-layer-masks.md) manually once it's added.
