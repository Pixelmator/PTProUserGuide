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

# Refine selections

After making a selection, you can use options in the Select and Mask tool to enhance it by adding or removing areas from an existing selection, adjusting its softness, roundness, size, or using the Smart Refine tool. After refining a selection, you can also choose what to do with it — add a mask created from the selection to the same or a duplicate layer, create a new layer with selection contents, or just keep it as a selection.

## Turn on the Select and Mask tool

1. Make a selection.
2.  Do one of the following:

    * With one of the selection tools active, click the Select and Mask button in the Tool Options pane.
    * Choose **Edit > Select and Mask** from the Edit menu at the top of your screen.
    * Choose **Tools > Select > Select and Mask** from the Tools menu at the top of your screen.
    * Press `Option ⌥` + `Command ⌘` + `R` on your keyboard.

    _Note:_ While the Select and Mask is active, your selection outline is replaced by an overlay. Any selected areas are see-through, while any unselected areas are colored in. Pixelmator Pro uses a yellow by default but you can choose red, black, white, or plain black & white overlay from the Overlay pop-up menu.

{% embed url="https://d2hh90bli6ucxp.cloudfront.net/help/selections/refine-selection-2.4.mp4" %}

### Manually refine the selection

1. Adjust the options in the Tool Options pane:
   * _Shape Roundness:_ Adjust how much to round the selection outline.&#x20;
   * _Edge Softness:_ Adjust how much to soften the edges of the selection outline. With softer edges, the selected area will blend in better with other parts of the image should you copy or edit it.
   * _Expand:_ Change the size of the selection.
2. In the Output pop-up menu, select what you'd like to do with your refined selection:
   * _Selection_: Applies the refined selection to a layer.
   * _Mask_: Applies a mask created from the refined selection to the active layer.
   * _New Layer with Mask_: Creates a duplicate of the active layer and applies a mask created from the refined selection.&#x20;
   * _New Layer_: Creates a new layer with the contents of the refined selection. Pixelmator Pro will automatically decontaminate the edges of the selection, removing any color left from the previous background.
3. Click Apply at the bottom of the Tool Options pane to apply your refinements to the selection.

### Automatically refine a selection using Smart Refine

Smart Refine uses a machine learning-based algorithm to intelligently detect intricate details like hair or fur at the selection edges and automatically refine the selection outline for you. To use Smart Refine:

1. Make a selection.
2. Do one of the following:
   * Choose **Edit > Smart Refine** from the Edit menu at the top of your screen.
   * Choose **Edit > Select and Mask** and click Smart Refine in the Tool Options pane.
   * Press `Option ⌥` + `Command ⌘` + `R` on your keyboard.
3. Click Apply at the bottom of the Tool Options pane to apply your refinements to the selection.

### Add or subtract areas from an existing selection

While the Select and Mask tool is active, you can use the selection refinement brush to paint over areas in your image to quickly edit your selection.&#x20;

1. Choose a brush type you want to use:
   * _Refine Edge Brush_: Adds or subtracts only at the edges of the selection.
   * _Quick Selection Brush_: Adds or subtracts from selection as if using the Quick Selection tool.
   * _Basic Brush_: Adds or subtracts from selection as if painting with a basic brush.
2. Choose the selection mode:
   * If the _Add_ selection mode is active, any areas you paint over will be added to your selection (and lose the color overlay).
   * If you choose the _Subtract_ selection mode, the areas you paint over will be removed from your selection (and will be covered by the color overlay).
3. Adjust the size and softness of the brush.
4. Paint over image areas you want to add or subtract from your selection.
