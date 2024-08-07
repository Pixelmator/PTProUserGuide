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

# Organize and manage layers

When working with more complex compositions that have many layers, you can use various layer management tools to make it easier to track all the layers in your image. For example, you can group certain layers, hide them if you don’t currently need to see or edit them, or lock them if you’d like to keep them visible but prevent them from being edited. You can also name layers, merge layers, and more.

## Manage individual layers

Managing layers in Pixelmator Pro lets you keep your documents neat and organized. You can rename layers to give them more recognizable names, merge layers to simplify complex designs, delete layers you no longer need, and lock or unlock layers to prevent accidental changes.

### Rename a layer

Renaming groups and layers in the Layers list helps organize your document.

To rename a layer do one of the following:

* In the Layers sidebar, double-click the layer name you want to change and type in a new name.
* In the Layers sidebar, force-click the layer name and type in a new one.

Pixelmator Pro also automatically names the layers you drag to the Layers sidebar from Finder or the web. You can `Control ⌃` – click the automatically named layer, choose Suggested Names and select another alternative name or revert to the original.

:bulb: **Tip:** If you'd like to turn off automatic layer naming completely, you can use the Terminal app on your Mac for this. You can enter the following Terminal flag or [learn more about using Terminal on a Mac](https://support.apple.com/en-gb/guide/terminal/welcome/mac).\
\
`defaults write com.pixelmatorteam.pixelmator.x enableSmartLayerNames -bool false`

### Merge multiple layers into a single layer

Merging (also called _flattening_) layers is a destructive action that combines a number of different layers into one. Any adjustments, effects, styles, or other formatting information are also flattened down into the image, so they will no longer be editable. Merging layers can be useful when you have a large image with many different layers that you won’t necessarily need to edit in the future and you want to make the image more manageable.

To merge two or more layers, do the following:

1. Select the layers you’d like to merge.
2. Then, do one of the following:
   * Choose **Arrange > Merge** from the Arrange menu at the top of your screen.
   * In the Layers sidebar, `Control ⌃` – click the layer (or layers) you’d like to merge and choose Merge. 
   * Press `Option ⌥` + `Command ⌘` + `E` on your keyboard.

To merge every layer in a composition:

* Choose **Arrange > Merge All** (from the Arrange menu at the top of your screen).
* Press `Option ⌥` + `Shift ⇧` + `Command ⌘` + `E` on your keyboard.

### Delete a layer

Do one of the following:

* In the Layers sidebar, `Control ⌃` – click the layer you'd like to delete and choose Delete.
* Select the layer you'd like to delete, then press `Backspace ⌫` on your keyboard.
* Select the layer you'd like to delete, then choose **Edit > Delete** from the Edit menu at the top of your screen.

### Lock or unlock layers or layer groups

When you lock a layer or layer group, it stays visible in your image but it will no longer be editable. However, locked layers and groups can still be deleted, renamed, and rearranged in the Layers sidebar.&#x20;

To lock or unlock a layer or layer group, do one of the following:

* Choose **Arrange > Lock** or **Arrange > Unlock** from the Arrange menu at the top of your screen. 
* In the Layers list, move the mouse pointer over the layer or layer group you’d like to lock and click <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1586802756000.png" alt="" data-size="line">. To unlock layers, click <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1586802719000.png" alt="" data-size="line">.
* In the Layers sidebar, `Control ⌃` – click a layer or layer group choose Lock or Unlock.



## Manage layer groups

You can group layers to apply effects and adjustments to all of them at a time, move or resize layers together, and create structure in more complex projects. Additionally, you can expand or collapse layer groups for a cleaner workspace, and hide or show layer groups without removing them from your composition.

### Group or ungroup layers

Grouping layers into layer groups lets you make your compositions more organized. It also lets you apply effects and adjustments to a number of layers together without having to merge them. When you move or resize a layer group, each layer is moved and resized together, in proportion. You can also group layers within layer groups to create nested groups.&#x20;

To group multiple layers into a layer group or to ungroup them:

1. [Select the layers](https://www.pixelmator.com/support/guide/pixelmator-pro/662) you'd like to group or ungroup.
2. Do one of the following:
   * Choose **Arrange > Group** or **Arrange > Ungroup** from the Arrange menu at the top of your screen.
   * In the Layers list, `Control ⌃` – click the layers you’d like to group or ungroup and choose Group or Ungroup.
   * Press `Command ⌘` + `G` on your keyboard to group, or `Shift ⇧` + `Command ⌘` + `G` to ungroup layers.

### Add layers to a layer group

Do one of the following:

* Select a layer inside an expanded layer group in the Layers sidebar (choose **View > Show Layers** if the Layers sidebar isn’t visible) and choose one of the options from the Insert menu at the top of your screen.
* Drag a layer to the layer group in the Layers sidebar.
* Drag a layer group onto another layer group. The group, together with all its layers, will be nested inside the layer group.

### Expand or collapse a layer group

To expand or collapse a single-layer group:

* In the Layers sidebar, click the disclosure triangle next to the layer group's name.

To expand or collapse a layer group and all the groups nested within it:

* In the Layers sidebar, `Option ⌥` – click the disclosure triangle next to the layer group's name.

### Hide or show a layer or layer group

In the Layers list, you can disable layers and groups to make them invisible in the canvas without removing them from your composition. For example, if a large image layer obstructs the layers below, you can temporarily hide it. If you hide a group, you also hide all layers and groups nested in it. However, hidden layers and groups can still be deleted, renamed, and rearranged in the Layers sidebar.

1. Select the layers you'd like to hide or reveal.
2. Do one of the following:
   * Choose **Arrange > Hide** or **Arrange > Show** from the Arrange menu at the top of your screen. 
   * Press `Option ⌥` + `Command ⌘` `+` , on your keyboard.
   * In the Layers sidebar, choose **View > Show Layers** if the list view isn’t visible, move the mouse pointer over the layer or layer group you’d like to hide or show and select or deselect the visibility checkbox. 
   * In the Layers sidebar, `Control ⌃` – click a layer or group and choose Hide or Show.

:blue\_book: **Note:** Hidden layers and groups are not included when your image is exported.

## Organize and sort layers

Organizing and sorting layers in Pixelmator Pro helps you navigate multi-layered documents more easily. You can add color tags to layers for easy identification and use layer filtering options to quickly view specific types of layers or find layers by name or color tag.

### Organize layers using color tags

You can add different color tags to layers to better organize multi-layered documents.

* To add a color tag, `Control ⌃` – click a layer and in the Tags section, pick a color.

### Filter layers based on the layer type, color tag, or name

You can use the layer filtering option to quickly view all group layers, masks, RAW and image layers, color adjustment and effect layers, shapes, or text in a document, or filter layers by their name or the assigned color tags.

To filter layers do one of the following:

* At the bottom of the Layers sidebar, start typing the layer name into the search field.&#x20;
* Click Filter <img src="https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1586516424000.png" alt="" data-size="line"> at the bottom of the Layers sidebar and pick the desired option.

To reset all filters, click Clear All.
