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

# About Pixelmator Pro sidecar files

Pixelmator Pro sidecar file is a special kind of Pixelmator Pro document that lets you save layers and nondestructive edits to regular image file formats — JPEG, PNG, TIFF, HEIF, or WebP — that don't normally support layers. The sidecar file gets attached to the original image and stores all its edits in the Pictures folder on your Mac or in iCloud.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1677169679000.jpeg)

### How saving edits using the sidecar feature is different from saving to a Pixelmator Pro document file?

1. [Pixelmator Pro documents](about-the-pixelmator-pro-file-format.md) can only be opened using Pixelmator Pro. This means that if you decide to share your edited image with someone else, post it online, or open it in other apps, you'd have to export it in any of the regular image formats. In the meantime, sidecar lets you work with the edited images just like you normally would without having to export them. Images with sidecar edits look and behave just like regular images in Finder.
2. Because the edited images do not have to be exported, lossy image file formats like JPEG can be edited virtually infinitely without losing quality.
3. When saving changes to sidecar, you don't have to create a duplicate of your image. The image remains in the same folder, keeping its original name. When you close and re-open the edited image in Pixelmator Pro, it will have all edits and layers available.
4. Sidecar offers seamless integration with Photos. If you open an image from Photos directly or use the Pixelmator Pro Photo browser, you can save the changes you make to the image back to Photos, preserving all layers and edits. See [Edit from Photos](edit-from-photos.md) to learn more about editing images from photos.

### What happens if you delete a sidecar file?

Deleting a sidecar file will merge all the changes and layers applied to the image, leaving only a flattened version of the edited image. Any further edits to the image will be applied destructively, unless sidecar is enabled for the image again. To re-enable sidecar, choose **File > Sidecar > Enable Sidecar**.

When editing images from Finder, we always recommend having Auto Save and macOS Versions turned on when editing images. This way, you'll be able to browse the previous version or revert the image to the original by choosing **File > Revert To > Browse All Versions**. For images edited with Auto Save and Versions turned off, changes will be applied permanently and irreversibly. Images opened from Photos can always be reverted back to the original in Photos.

To save space on your device, you can regularly delete sidecar files manually or using automated options in [Pixelmator Pro settings](../pixelmator-pro-basics/pixelmator-pro-settings/).

## Open images in their original file format

1. Choose **Pixelmator Pro > Settings** (from the Pixelmator Pro menu at the top of your screen).
2. In the Editing tab, click the Open Images In pop-up menu and choose Original Format.
3. Under Preserve Edits, choose how to save edits:
   * Select _For Images Opened from Finder_ to save images back to their original folder in Finder, keeping the original file format, and preserving all layers and edits. Deselect _For Images Opened from Finder_ to overwrite original images when saving.
   * Select _For Images Opened from Photos_ to save photos opened from your photo library or use the Photos extension back to the photo library while preserving all layers and edits. Deselect _For Images Opened from Photos_ to overwrite original photos in the photo library when saving.

:blue\_book: **Note:** To continue editing an image saved to Photos, open it again using the Photo browser or the Pixelmator Pro extension in Photos. Dragging the image from Photos to Pixelmator Pro directly, or choosing **Edit With > Pixelmator Pro** from the image shortcut menu in Photos will open a flattened version of the image in Pixelmator Pro.

## Choose the sidecar file location

To choose where the Pixelmator Pro sidecar files will be saved on your Mac:

1. Choose **Pixelmator Pro > Settings** (from the Pixelmator Pro menu at the top of your screen).
2. In the Editing tab, under Save Sidecar Files In, choose one of the following:
   * _iCloud_. Saves Pixelmator Pro sidecar files in a dedicated folder in iCloud. You can use this option if you work with Pixelmator Pro across multiple devices or if you are looking to save space on your Mac.
   * _Pictures_. Saves Pixelmator Pro sidecar files in a dedicated folder on your Mac, which is recommended if you tend to do most of your work offline.

## Manage sidecar files

In the Editing settings, you can keep track of the number of Pixelmator Pro sidecar files on your Mac and just how much space they take up on your Mac. If you'd like to manage your sidecar files, you can click Manage Files to open the dedicated Sidecar folder and find all the sidecar files there.

Alternatively, you can choose **File > Sidecar > Reveal Sidecar File** to reveal a sidecar file of a specific image you've opened.

:blue\_book: **Note:** Sidecar files are not managed for you automatically. For instance, if you manually unlink the sidecar file from an edited image or delete the edited image from your Mac completely, its sidecar file will not be deleted.

### To delete a sidecar file, do any of the following:

* Choose **File > Sidecar > Reveal Sidecar File** and delete the sidecar file from your Mac.
* Choose **File > Sidecar > Delete Sidecar File**.

:blue\_book: **Note:** If you delete the sidecar file without deleting the linked image, all edits will be merged the next time you open the image. If, however, you had Auto Save and Versions option turned on, you can still revert the image to the original using **File > Revert To > Browse All Versions**.
