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

# Export and share images

Pixelmator Pro is a nondestructive, layer-based image editor. In order to preserve all the formatting, layers, and additional image information, Pixelmator Pro uses its own special — [PXD](https://www.pixelmator.com/support/guide/pixelmator-pro/639) — file format. However, when you want to use an image or video on the web or share it with someone who uses a different image editor, you should export it to a different file format. You can also export images specially  [optimized for the web](https://www.pixelmator.com/support/guide/pixelmator-pro/1051).

1. Do one of the following:
   * Choose **File > Export** from the File menu at the top of your screen.
   * Press `Command ⌘` + `E` on your keyboard.
2.  In the Export dialog (shown below) enter a name in the Save As field, then enter one or more [tags](https://www.pixelmator.com/support/guide/pixelmator-pro/#glossary) (optional).

    ![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1651059548000.jpeg)
3. To choose where to export the image, click the Locations pop-up menu, or the disclosure button next to it, then choose a location (for example, a folder or your desktop).
4.  Customize the export file — choose a file format, color profile, quality, size, etc. The available options vary based on the file format selected.

    :blue\_book: **Note:** When resizing images for export, Pixelmator Pro uses the most universal, Bilinear scaling algorithm. It works best for scaling down images. If, instead, you'd like to upscale your image (using Super Resolution) or use a different algorithm for downscaling, you can do so in the [Image Size](https://www.pixelmator.com/support/guide/pixelmator-pro/1006) menu before export.&#x20;
5. Click Export.

## Image formats

### HEIC

The HEIC or High Efficiency Image File format is a modern format that can greatly reduce the image size without visibly affecting its quality. On average, it's around 50% more efficient than JPEG.

Customize the HEIC file:

_Quality:_ Drag the quality slider or enter the precise quality percentage to change the level of HEIC compression. Exporting between 75% to 85% quality can greatly reduce the image size without any noticeable drop in quality. Higher levels of compression will make images lighter but can potentially reduce their quality.&#x20;

_Size:_ Click the Size pop-up menu to choose whether to export the image at its original size, enter a custom size, or choose a specific scaling.

### JPEG

The JPEG file format is a popular format for photographic images on the web. It uses lossy compression to reduce file sizes and also has a variable quality setting that allows you to reduce the size of an image by potentially reducing its quality. Generally, exporting an image to JPEG above 75% or 80% quality will greatly reduce its size without any visible drop in quality.

Customize the JPEG file:

_Color Profile:_ JPEG images are typically exported using the original color profile of the file, but you can click the Color Profile pop-up menu to choose a different one for export.

_Quality:_ Drag the quality slider or enter the precise quality percentage to change the level of JPEG compression. Exporting between 75% to 85% quality can greatly reduce the image size without any noticeable drop in quality. Higher levels of compression will make images lighter but can potentially reduce image quality.&#x20;

_Size:_ Click the Size pop-up menu to choose whether to export the image at its original size, enter a custom size, or specific scaling.

PNG

The PNG format is most often used for exporting images with transparency. PNG files tend to be relatively larger images than JPEGs.

Customize the PNG file:

_Color Profile:_ PNG images are typically exported using the original color profile of the file, but you can click the Color Profile pop-up menu to choose a different one for export.

_Size:_ Click the Size pop-up menu to choose whether to export the image at its original size, enter a custom size, or specific scaling.

### WebP

Due to smaller file sizes, WebP is a popular file format for displaying images on the web. WebP files support transparency and are around 25% smaller than comparable PNGs and JPEGs of the same quality.

Customize the WebP file:

_Color Profile:_ WebP images are typically exported using the original color profile of the file, but you can click the Color Profile pop-up menu to choose a different one for export.

_Quality:_ Drag the quality slider or enter a precise quality percentage to change the level of WebP compression. At 100% quality, you get lossless compression, like with PNG. At 99% quality or lower, you get lossy compression, like with JPEG.

_Size:_ Click the Size pop-up menu to choose whether to export the image at its original size, enter a custom size, or choose a specific scaling.

### TIFF

The TIFF or Tagged Image File Format is a lossless, raster image format that supports transparency and is popular among graphic designers and photographers. TIFF files are usually larger than JPEGs and can be exported compressed or uncompressed.&#x20;

Customize the TIFF file:

_Color Profile:_ TIFF images are typically exported using the original color profile of the file, but you can click the Color Profile pop-up menu to choose a different one for export.

_Compression:_ Turn on compression to compress the file using lossless compression or turn compression off to export it uncompressed. TIFF compression is lossless so all the image information is preserved, even if the file size is reduced.

_Size:_ Click the Size pop-up menu to choose whether to export the image at its original size, enter a custom size, or specific scaling.

### SVG

The SVG (Scalable Vector Graphics) format is a vector file format. SVG images and their properties are defined in XML text files, so SVG images can be created and edited with any text editor, as well as graphics software.

Export an image to Pixelmator Pro format

Typically, to save Pixelmator Pro-native [PXD](https://www.pixelmator.com/support/guide/pixelmator-pro/639) files, you use the **File > Save** (from the File menu at the top of your screen) command. However, you can also export to PXD if your workflow requires it.

### PSD

The PSD file format offers layer support and can be opened in other apps that work with PSD files.

_Optimize for Apple pro apps:_ Convert shapes or Pixelmator Pro-specific, nondestructive effects and color adjustments to pixels.

### Motion Project

Motion is an Apple Pro app, dedicated to creating motion graphics on a Mac. Pixelmator Pro supports Motion text layers, basic and complex shapes, image layers, and drop shadows, so the projects you export to Motion look just how you designed them in Pixelmator Pro.

Pixelmator Pro also lets you seamlessly convert SVG files to Motion-ready projects. If you have an SVG file you'd like to use for your motion graphic, you can export it as a Motion Project file and continue working with it in Motion.

Customize the Motion Project file:

_Frame Rate:_ Enter the desired frame rate in frames per second (FPS). The frame rate you choose should match the type of your final project. E.g.: films use 24 fps, PAL video — 25 fps, NTSC video — 29.97 fps, etc.&#x20;

_Duration:_ Enter the desired Timeline duration of your Motion Project in seconds.

### PDF

The PDF or Portable Document Format is a format primarily used for reading and producing documents, including text and images. Pixelmator Pro can import and export single-page, raster PDFs.

Customize the PDF file:

_Color Profile:_ PDFs are typically exported using the original color profile of the file, but you can click the Color Profile pop-up menu to choose a different one for export.

_Size:_ Click the Size pop-up menu to choose whether to export the image at its original size, enter a custom size, or specific scaling.

_Flatten layers:_ Select flatten layers to export the PDF with all layers merged into a single image (bitmap PDF). Or deselect it to preserve all layers (vector PDF).&#x20;

### JPEG-2000

JPEG-2000 is a flexible, raster image format that lets you either to compress the file or export it uncompressed and retain original image detail. JPEG-2000 offers better compression performance and fewer artifacts compared to the original JPEG format but is not as widely adopted.

Customize the JPEG-2000 file:

_Color Profile:_ JPEG-2000 images are typically exported using the original color profile of the file, but you can click the Color Profile pop-up menu to choose a different one for export.

_Quality:_ Drag the quality slider or enter a precise quality percentage to change the level of JPEG-2000 compression. Exporting between 75% to 85% quality can greatly reduce the image size without any noticeable drop in quality. Higher levels of compression will make images lighter but can potentially reduce image quality.&#x20;

_Size:_ Click the Size pop-up menu to choose whether to export the image at its original size, enter a custom size, or choose a specific scaling.

### GIF

The GIF or Graphics Interchange Format is a raster image format. GIF images support 8-bit color depth and can display 256 different colors from the 24-bit RGB color space. GIF file format is suitable for exporting simple graphics such as solid-color logos but may bring out unwanted artifacts in color gradients or photos.

_Size:_ Click the Size pop-up menu to choose whether to export the image at its original size, enter a custom size, or choose a specific scaling.

### BMP

BMP is a raster image format, primarily used for legacy purposes only. BMP doesn't use uncompression, making the file sizes of the exported images larger.&#x20;

_Size:_ Click the Size pop-up menu to choose whether to export the image at its original size, enter a custom size, or choose a specific scaling.

## Video formats

### MP4

MP4 (or MPEG-4) is one of the most popular and versatile video formats. MP4 files use advanced compression that makes them lightweight and quick to load on the web.

Customize the MP4 file:

_Quality:_ Drag the quality slider or enter a precise quality percentage to change the level of MP4 compression.

_Frame Rate:_ Enter the desired frame rate in frames per second (FPS). E.g.: films use 24 fps, PAL video — 25 fps, NTSC video — 29.97 fps, etc.&#x20;

_Size:_ Click the Size pop-up menu to choose whether to export the video at its original size, enter a custom size, or choose a specific scaling.

:blue\_book: **Note:** Video formats do not support non-even dimensions (e.g.: 199x199 px). When exporting videos, always make sure you choose a supported size, otherwise, the dimensions will be rounded automatically and the video may become distorted.

### QuickTime Movie

QuickTime Movie is a video format created by Apple. In many ways, QuickTime Movie is similar to MP4, so both formats can be used interchangeably.

Customize the QuickTime Movie file:

_Compression type:_ When exporting videos or video compositions to QuickTime Movie, you can choose from a range of different video compression types, including H.264, HEVC, HEVC with Alpha, and Apple ProRes codecs.

_Frame rate:_ Enter the desired frame rate in frames per second (FPS). E.g.: films use 24 fps, PAL video — 25 fps, NTSC video — 29.97 fps, etc.&#x20;

_Size:_ Click the Size pop-up menu to choose whether to export the video at its original size, enter a custom size, or choose a specific scaling.

_Note:_ Video formats do not support non-even dimensions (e.g.: 199x199 px). When exporting videos, always make sure you choose a supported size, otherwise, the dimensions will be rounded automatically and the video may become distorted.

### Animated GIF

Animated GIF (or the Graphics Interchange Format) is a bitmap image format that can be animated, supports transparency, and uses a color palette of up to 256 colors.&#x20;

Customize the animated GIF file:

_Frame Rate:_ Enter the desired frame rate in frames per second (FPS). Keep in mind, that GIFs with frame rates above 50 FPS are not supported on the web. Videos with higher frame rates will be played at 10 FPS instead.

_Size:_ Click the Size pop-up menu to choose whether to export the video at its original size, enter a custom size, or choose a specific scaling. The animated GIF format works best with short video clips. If the exported GIF is too big, try reducing the dimensions, FPS, or quality of the video to reduce its file size.&#x20;

:blue\_book: **Note:** Video formats do not support non-even dimensions (e.g.: 199x199 px). When exporting videos, always make sure you choose a supported size, otherwise, the dimensions will be rounded automatically and the video may become distorted.

### Animated PNG

Animated PNGs work similarly to GIFs, with an addition of support for 24-bit images and 8-bit transparency.

Customize the animated PNG file:

_Frame Rate:_ Enter the desired frame rate in frames per second (FPS).

_Size:_ Click the Size pop-up menu to choose whether to export the video at its original size, enter a custom size, or choose a specific scaling.

_Note:_ Video formats do not support non-even dimensions (e.g.: 199x199 px). When exporting videos, always make sure you choose a supported size, otherwise, the dimensions will be rounded automatically and the video may become distorted.
