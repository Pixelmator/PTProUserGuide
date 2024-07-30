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

# Zoom in and out of an image

You can zoom in and out of an image to make it easier to work on large images or work on smaller details.

***

### Zoom in or out of an image

Do any of the following:

* Drag the Zoom slider in the toolbar.
* If you’re using a MacBook with a Multi-Touch trackpad or the Magic Trackpad, move the mouse pointer over your image, then pinch using two fingers to zoom in or out.
* Choose **View > Zoom In** or **View > Zoom Out** (from the View menu at the top of the screen).
* Press `Command ⌘` and Plus `+` on your keyboard to zoom in, or `Command ⌘` and Minus `-` to zoom out.
* `Option ⌥` – scroll an image.
* Click "100%" in the [toolbar](https://about/support/guide/pixelmator-pro/#glossary), then select an option (if the zoom button is not visible, you can choose **Window > Customize Toolbar** to add it):
  * _A percentage:_ The image zooms in or out accordingly.
  * _Zoom to fit:_ The image adjusts to fill the application window. If you enlarge or reduce the size of the Pixelmator Pro application window, the zoom level changes so that the image always fills the window.
  * _Enter a value:_ You can also zoom in on an image by entering a specific zoom percentage. Double-click the number field to enter the desired value.
* Use the Zoom tool.

### Zoom an image to fit the application window

Do one of the following:

* Double-click the Zoom slider.
* Press Command ⌘ + 0 on your keyboard.
* Click <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1580998676000.png" alt="" data-size="line"> in the Tools sidebar and click Actual Size in the Tool Options pane.
* Choose **Tools > Zoom** (from the Tools menu at the top of your screen) and click Zoom to Fit in the Tool Options pane.
* Choose **View > Zoom to Fit** (from the View menu at the top of your screen).

### View an image at its actual size

Do one of the following:

* Choose **View > Actual Size** from the View menu at the top of your screen.
* Press `Option ⌥` + `Command ⌘` + `0` or `Command ⌘` + `1` on your keyboard.
* Click <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1580998676000.png" alt="" data-size="line"> in the [Tools sidebar](https://about/support/guide/pixelmator-pro/#glossary) and click Actual Size in the [Tool Options pane](https://about/support/guide/pixelmator-pro/#glossary).
* Choose **Tools > Zoom** (from the Tools menu at the top of your screen) and click Actual Size in the Tool Options pane. This displays the image as it would appear in a web browser.

{% hint style="warning" %}
Pixelmator Pro is optimized for the Retina display, so if you have a Mac computer with a Retina display, keep in mind that the image will appear twice as small as on other displays or in apps like Preview. To view the image as it would appear on those displays or on a website not optimized for Retina, set the zoom percentage to 200%.
{% endhint %}

***

## Use the Zool tool

The Pixelmator Pro Zoom tool lets you zoom in and out of the image using the zoom slider, zoom modes, and more.

1. Choose the Zoom tool by doing one of the following:
   * Click <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1580998676000.png" alt="" data-size="line"> in the Tools sidebar.
   * Choose **Tools > Zoom** (from the Tools menu at the top of your screen).
   * Press `Z` on your keyboard.
2. Do any of the following:
   * In the Tool Options pane, drag the Zoom slider to zoom in or out of the image. You can also use the Navigator box to change the area of an image on which you’re zoomed in.
   * Click the disclosure triangle next to the current zoom to choose a default zoom percentage, or type in a custom zoom percentage into the percentage field.
   * Under Mode, select Zoom In or Zoom Out and click the area of an image that you’d like to zoom in or zoom out.

### Zoom using the scrubby zoom

In the Zoom tool options, you can use scrubby zoom to zoom an image by clicking and dragging over it.

1. To turn on scrubby zoom do one of the following:
   * In the Zoom tool options select Scrubby Zoom.
   * When a different tool is selected, press and hold `Space` + `Option ⌥` on your keyboard.
2. Drag left or right on the canvas to zoom in and out of an image.

If you'd like to zoom by dragging your pointer on a vertical axis instead, you can use the Terminal app on your Mac to change the default behavior. You can enter the following Terminal flag or [learn more about using Terminal on a Mac](https://support.apple.com/en-gb/guide/terminal/welcome/mac):

```markup
defaults write com.pixelmatorteam.pixelmator.x enableVerticalScrubbyZoom -bool true
```
