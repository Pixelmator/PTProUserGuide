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

# Open an image

You can open images in a variety of different image formats saved on your Mac, in iCloud Drive, on connected servers, and third-party storage providers. The following file formats are supported in Pixelmator Pro: PXD, JPEG, PNG, TIFF, HEIC, PSD, SVG, PDF, GIF, BMP, TGA, WebP, JPEG-2000, macOS-supported RAW formats.

## Open an existing document

* _Open an image or a document on your Mac:_ Launch Pixelmator Pro and in the welcome screen, click "Browse files on your Mac". To open images directly from their original locations on your Mac, drag the images or documents onto the Pixelmator Pro icon in the Dock. You can also `Control ⌃`-click the file in its folder and choose **Open With > Pixelmator Pro**.
* _Open an image you recently worked on:_ Launch Pixelmator Pro and in the welcome screen, choose from the recently opened images on the right. You can also choose **File > Open Recent** (from the File menu at the top of your screen). To change the number of recent documents displayed, go to macOS **System Preferences > General**, and choose a number from the Recent items pop-up menu.
* _Open an image from macOS Photos:_ Launch Pixelmator Pro and in the welcome screen, choose "Open the Photos browser". You can also choose **File > New from Photos** to open the Photos browser. In the sidebar on the left, browse the Photos albums to locate an image you'd like to import. Select and click OK, or simply double-click the image thumbnail to open the image.
* _Open an image stored somewhere else than your Mac (such as iCloud Drive):_ Launch Pixelmator Pro and in the welcome screen, click "Browse files on your Mac". Click the pop-up menu at the top of the Open dialog (shown below) that appears, then choose the location where the image is saved. Locate and double-click a file to open it.

:bulb: **Tip:** You can also open images by simply dragging them from a website on Safari or a folder in Finder onto the Pixelmator Pro icon in the Dock.

![](.gitbook/assets/Pixelmator-Pro\_Open-an-existing-document.png)

Typically when you open an image in Pixelmator Pro it gets automatically converted to PXD — the [Pixelmator Pro file format](create-open-and-save-images/about-the-pixelmator-pro-file-format.md) — so when you save the image, any additional layers and advanced formatting you add are not lost and remain editable. Once you finish editing and would like to share an image with someone else or upload it online, you can save it as a JPEG, PNG, TIFF, WebP, or HEIC image or [export](export-and-share-images/) it.

Alternatively, instead of importing images as PXD documents, you can choose to [open them in their original file format](pixelmator-pro-basics/pixelmator-pro-settings/editing-settings.md) — JPEG, PNG, TIFF, WebP, or HEIC — and save changes directly back to the same file format using sidecar files. This workflow lets you share the edited images directly, without having to export them first. You can learn more about different editing workflows in Pixelmator Pro and change how it opens images in the article about Editing settings.

## Opening vector and bitmap PDFs

In Pixelmator Pro, you can choose to open PDF documents as bitmaps (an image-based type of PDF), or vector PDFs (PDFs that support layers). Vector PDFs let you edit shape and image elements in PDFs as separate layers and scale documents to any size without losing quality. Bitmap PDFs open with all their contents merged into a single page which also has a fixed resolution. Because of this, bitmap PDFs have more limited options for editing and may lose quality when upscaling.

When opening multi-page PDFs in Pixelmator Pro, you can also choose which page you'd like to open and edit.

1. Open a PDF document in Pixelmator Pro.
2. In the PDF open dialog, choose how to open the PDF document:
   * For multi-page PDFs, browse the list of pages on the left to select the one you wish to open.
   * Adjust the Width and Height of the PDF document and set the desired resolution.
   * To open the document as a vector PDF with layers, make sure "Import PDF with layers" is selected. Deselect this option if you want to import a flattened, bitmap PDF.
3. Click Import.

When you open a Pixelmator Pro document that uses fonts not installed on your Mac, a missing font notification appears briefly at the top of the image. In the notification, click Show and choose a replacement font.
