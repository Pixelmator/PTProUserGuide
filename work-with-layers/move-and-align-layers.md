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

# Move and align layers

You can move and align any layer or multiple layers using the Arrange <img src="../.gitbook/assets/Arrange.png" alt="" data-size="line"> tool. You can move layers around manually or enter specific coordinates of where exactly on the canvas you want your layer to be placed.

## Move a layer

1. Choose the Arrange tool by doing one of the following:
   * Click Arrange <img src="../.gitbook/assets/Arrange.png" alt="" data-size="line"> in the Tools sidebar.
   * Choose **Tools > Arrange** from the Tools menu at the top of your screen.
   * Press the `V` key on your keyboard.
2. Do any of the following:&#x20;
   * _Move a layer:_ Drag the layer on the canvas to move it.
   * _Move a layer by one pixel:_ Press an arrow key.
   * _Move a layer by ten pixels:_ Press and hold the `Shift ⇧` key while you press an arrow key.

When you move layers, they automatically snap to other layers on the canvas. You can press and hold the `Command ⌘` key to temporarily disable snapping, or deselect the alignment guides in the View menu at the top of the screen to turn off snapping completely.

## Position a layer using x and y coordinates

1. Choose the Arrange tool by doing one of the following:
   * Click Arrange <img src="../.gitbook/assets/Arrange.png" alt="" data-size="line"> in the Tools sidebar.
   * Choose **Tools > Arrange** from the Tools menu at the top of your screen.
   * Press the `V` key on your keyboard.
2. [Select the layer](select-layers.md) you'd like to position.
3.  Enter x and y values in the Position fields. 

    * The x value is measured from the left edge of the canvas to the object’s upper-left corner. 
    * The y value is measured from the top edge of the canvas to the object’s upper-left corner.

    When you drag an object, its x and y coordinates are displayed.

    To change the units used for the x and y coordinates `Control ⌃` – click the number field and choose a different unit.

{% embed url="https://d2hh90bli6ucxp.cloudfront.net/help/layers/layer-position-change-2.4.mp4" %}

## Align objects vertically or horizontally

You can align objects so they line up along a vertical or horizontal axis.

1. Do one of the following:
   * Click Arrange <img src="../.gitbook/assets/Arrange.png" alt="" data-size="line"> in the Tools sidebar.
   * Choose **Arrange > Align Objects** from the Arrange menu at the top of your screen.
2. Select the layer you'd like to align. If one layer is selected, it aligns to the canvas. If two or more layers are selected, the layers align to the layer which is closest to the direction you selected. For instance, if you align three layers to the left, the leftmost layer doesn’t move, and the other objects align to it.
3.  Click one of the alignment buttons below the layer order slider in the Tool Options pane or choose one of the alignment options:

    \
    <img src="../.gitbook/assets/Align_Top-Edges.png" alt="" data-size="line"> _Top Edges:_ Aligns all your selected layers to the top edge of the topmost layer.\
    \
    <img src="../.gitbook/assets/Align_Vertical-Centers.png" alt="" data-size="line"> _Vertical Centers:_ Vertically moves all your selected layers to align them along one central horizontal axis.\


    <img src="../.gitbook/assets/Align_Bottom-Edges.png" alt="" data-size="line"> _Bottom Edges:_ Aligns all your selected layers to the bottom edge of the bottom layer.\
    \
    <img src="../.gitbook/assets/Align_Left-Edges.png" alt="" data-size="line"> _Left Edges:_ Aligns all your selected layers to the left edge of the leftmost layer.\
    \
    <img src="../.gitbook/assets/Align_Horizontal-Centers.png" alt="" data-size="line"> _Horizontal Centers:_ Horizontally moves all your selected layers to align them along one central vertical axis.\
    \
    <img src="../.gitbook/assets/Align_Right-Edges.png" alt="" data-size="line"> _Right Edges:_ Aligns all your selected layers to the right edge of the rightmost layer.

You can also align objects to selections — for example, if you make a selection with the Rectangular Selection tool, any objects will align to the edges of the selection.

## Equally distribute objects

Distributing layers lets you arrange them according to their edges or centers. For example, you can automatically space objects to set equal distances between every left edge.

1. Click Arrange <img src="../.gitbook/assets/Arrange.png" alt="" data-size="line"> in the Tools sidebar.
2. Select three or more layers you’d like to equally space.
3.  Click one of the alignment buttons below the layer order slider in the Tool Options pane or choose one of the distribution options (you can also choose **Arrange > Distribute Objects** and select an option):\


    <img src="../.gitbook/assets/Equally_Top-Edges.png" alt="" data-size="line"> _Top Edges:_ Equally space any layers between the top and bottom selected layers according to their top edges.\


    <img src="../.gitbook/assets/Equally_Vertical-Centers.png" alt="" data-size="line"> _Vertical Centers:_ Equally space any layers between the top and bottom selected layers according to their vertical centers.\


    <img src="../.gitbook/assets/Equally_Bottom-Edges.png" alt="" data-size="line"> _Bottom Edges:_ Equally spaces any layers between the top and bottom selected layers according to their bottom edges.\


    <img src="../.gitbook/assets/Equally_Left-Edges.png" alt="" data-size="line"> _Left Edges:_ Equally spaces any layers between the leftmost and rightmost selected layers according to their left edges.\


    <img src="../.gitbook/assets/Equally_Horizontal-Centers.png" alt="" data-size="line"> _Horizontal Centers:_ Equally spaces any layers between the leftmost and rightmost selected layers according to their horizontal centers.\


    <img src="../.gitbook/assets/Equally_Right-Edges.png" alt="" data-size="line"> _Right Edges:_ Equally spaces any layers between the leftmost and rightmost selected layers according to their right edges.

## Evenly space objects of different sizes

Distributing layers vertically or horizontally lets you automatically create equal spaces between them.

1. Select three or more layers you’d like to equally space.
2.  Do one of the following:\
    \
    _Equally space objects across a vertical axis:_

    * Choose **Arrange > Distribute Objects > Vertical Spacing** from the Arrange menu at the top of your screen.
    * Press `Option ⌥` + `Command ⌘` + `Control ⌃` + `V`

    _Equally space objects across a horizontal axis:_

    * Choose **Arrange > Distribute Objects > Horizontal Spacing** from the Arrange menu at the top of your screen.
    * Press `Option ⌥` + `Command ⌘` + `Control ⌃ + H`
