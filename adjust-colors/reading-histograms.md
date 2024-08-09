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

# Reading histograms

A histogram is a graph that shows the overall distribution of tones or colors in an image. When discussing tonal range, the word _shadows_ is used to refer to the dark areas of an image, _highlights_ to the bright areas, and _midtones_ for all the neutral tones in between. Tonal range means the distribution of all the tones — from the darkest to the brightest — in an entire image.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1588149132000.png)

Pixelmator Pro features three different histograms — an RGB histogram, a luminance histogram, and a color histogram. Each of these histograms tells you about the distribution of tones or colors in the image in slightly different ways.

## RBG histogram

The RGB histogram is the default histogram in Pixelmator Pro. It shows you all the tones in your image, from pure black on the left edge to pure white on the right edge of the histogram. The higher the graph is at a given point, the more of the tone is in the image. Therefore, a fairly dark image with lots of shadows will have a histogram that is higher on the left side (the shadows), while a fairly bright image will have a histogram that is higher on the right side (the highlights). The reason the histogram is known as an RGB histogram is that digital images are composed of a mix of three colors — red, green, and blue. These are used to create every other color.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1591963450000.png)

Technically, this histogram shows the amount of each color (or channel) in the image and if separate areas of an image are pure red, pure green, and pure blue, the right side of the histogram will also be high.

## Luminance histogram

The luminance histogram displays the perceived brightness of an image. It doesn’t look at the individual color channels but at the colors themselves. So, unlike in the RGB histogram, pure blue will not be at the far right edge of the luminance histogram. And the luminance histogram also takes into account the fact that the human eye perceives green light as naturally brighter than red or blue. So any pure green areas will show up further right than pure blue or pure red areas.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1591963437000.png)

## Color histogram

The color histogram shows the overall distribution of each color range in an image — red, orange, yellow, green, cyan, blue, violet, and magenta.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1591963397000.png)

Color histograms can be useful in determining if any colors in an image have been clipped. If a color channel is clipped, the image areas of that particular color lose texture.

## Show or hide the histogram

1. Do one of the following:
   * Choose **Format > Color Adjustments** from the Format menu at the top of your screen.
   * In the Tools sidebar, click Color Adjustments <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1581000192000.png" alt="" data-size="line">.
2. Scroll down the list of color adjustments and click Customize.
3. Click to select or deselect Histogram. Alternatively, choose **Format > Color Adjustments > Histogram** from the Format menu at the top of your screen.

## Change the histogram type

1. Do one of the following:
   * Choose **Format > Color Adjustments** from the Format menu at the top of your screen.
   * In the Tools sidebar, click Color Adjustments <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1581000192000.png" alt="" data-size="line">.
2. Scroll down the list of color adjustments and click Customize.
3. Hover your pointer over the Histogram adjustment and click the disclosure arrow to show more options.
4. Choose the histogram type. Alternatively, choose **Format > Color Adjustments > Histogram** from the Format menu at the top of your screen and choose the histogram type.

## Pin the histogram adjustment

You can pin the histogram adjustment to always stay at the top of the Color Adjustments pane.

1. Do one of the following:
   * Choose **Format > Color Adjustments** from the Format menu at the top of your screen.
   * In the Tools sidebar, click Color Adjustments ![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1581000192000.png).
2. Scroll down the list of color adjustments and click Customize.
3. Hover your pointer over the Histogram adjustment and click the disclosure arrow to show more options.
4. Click Pin Histogram. Alternatively, choose **Format > Color Adjustments > Histogram** from the Format menu at the top of your screen and choose Pin Histogram.
