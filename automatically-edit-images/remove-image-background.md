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

Do any of the following:

* Click the Remove Background button in the toolbar. If it's not visible by default, you can add it in the Customize Toolbar menu. Choose **Window > Customize Toolbar** to open the menu, then drag the Remove Background item to the toolbar.\
  \
  :blue\_book: **Note:** In case there are multiple subjects in your image, you can use any of the [selection tools](../make-selections/) to mark only the ones you'd like to keep. The background removal algorithm may still remove areas within your selection if these are not identified as subjects.\

* Choose **Edit > Remove Background** from the Edit menu at the top of your screen.
* Press `Shift ⇧` + `Backspace ⌫` on your keyboard.
* While pressing and holding the `Command ⌘` key, drag and drop an image from your Mac or the web to the Layers sidebar.
* `Control ⌃` – click a layer or a layer group in the Layers sidebar and choose Remove Background.\
  \
  :bulb: **Tip:** When removing the background from a layer group, Pixelmator Pro creates a layer mask for that layer group. To delete the background completely, the Remove Background action would have to be performed on each layer within the group individually.\

* Choose **Tools > Smart Erase** from the Tools menu at the top of the screen and click Remove Background.

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLT86jsJoVnFy3L9z7CMi%2Fuploads%2FalYiuOZBiwVI7f3ndRXM%2FremoveBackground.mp4?alt=media&token=b13eb712-81f4-455a-aa63-22ae632c066b" %}

***

If you'd like to [Hide Background](hide-image-background.md) instead of removing it completely, hold down the `Option ⌥` key when clicking Remove Background in the menu. This will mask the background instead of deleting it and you'll be able to [edit the mask](../add-masks/working-with-bitmap-masks.md) manually once it's added.
