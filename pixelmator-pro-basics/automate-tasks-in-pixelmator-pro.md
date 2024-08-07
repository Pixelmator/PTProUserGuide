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

# Automate tasks in Pixelmator Pro

Pixelmator Pro lets you automate simple, repetitive tasks or execute complex workflows to improve productivity, save time, and reduce the chance of mistakes. There are a few automation options you can go for — using the Shortcuts app, writing commands in AppleScript, or using the Automator app. The below article discusses all of these methods and their possible uses.

***

### Use the Shortcuts app

The Shortcuts app offers one of the quickest and easiest ways of processing multiple images at a time using Pixelmator Pro tools and features. Images are processed in the background, so Pixelmator Pro itself doesn't even need to be running.

In the Shortcuts app, you'll find 29 different Pixelmator Pro actions that you can use on their own or in conjunction with actions from other apps to unlock even more workflow possibilities.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1635146380000.png)

See our tutorial on [batch processing images with Shortcuts](https://www.pixelmator.com/tutorials/video/automation-magic-with-shortcuts-and-pixelmator-pro/) to learn more about working with the Shortcuts app or check out [a collection of sample shortcuts](http://upload-cdn.pixelmator.com/Pixelmator-Pro-Shortcuts.zip) created by the Pixelmator Team for inspiration.

***

### Automate tasks with AppleScript

AppleScript is an Apple-created programming language that lets you automate different tasks in Pixelmator Pro by giving it explicit commands in code form. Tasks from other scriptable apps can also be combined into a workflow, making the automation options virtually unlimited. AppleScript uses an English-like language to tell apps what specific actions need to be performed, so it's pretty easy to write and edit scripts with very little or no programming experience whatsoever — often, you can understand what a particular script does by simply reading it.

The key things you need to write a script for Pixelmator Pro are:

1. **The Script Editor application.** Here is where you write, edit, and compile scripts. There's nothing special you need to do to install the Script Editor — it comes with your Mac.
2. **AppleScript syntax.** Lexical conventions, keywords, characters, symbols, and other language elements that are used to write statements and commands. See [Mac Automation Scripting Guide](https://developer.apple.com/library/archive/documentation/AppleScript/Conceptual/AppleScriptLangGuide/conceptual/ASLR\_lexical\_conventions.html#//apple\_ref/doc/uid/TP40000983-CH214-SW1) to learn more about scripting syntax.
3. **Pixelmator Pro scripting dictionary.** The dictionary lists all the commands, elements, and properties related to the specific actions, tools, and settings within Pixelmator Pro. To access the Pixelmator Pro scripting dictionary, choose **File > Open Dictionary** in the Script Editor and choose Pixelmator Pro from the list.

When learning any new programming language, the traditional project to start with is displaying a simple "Hello, world!" message. In Pixelmator Pro, this would include creating a new document and then adding a text layer containing this message.

To write your first "Hello, world!" script:

1. Open the Script Editor. If it's not in your Dock, launch it from the Launchpad or try searching for it using Spotlight Search.
2. In the Script Editor Open dialog, click New Document or choose **File > New** from the File menu at the top of your screen.
3. Enter the following script:

{% tabs %}
{% tab title="AppleScript" %}
{% code overflow="wrap" %}
```applescript
 tell application "Pixelmator Pro"
      activate
      set helloWorldDocument to make new document¬
                             with properties {width:5120, height:2880}
      tell helloWorldDocument
          set helloWorldText to make new text layer at the beginning of¬
                             layers with properties {text content:"Hello, world!"}
      end tell
  end tell
```
{% endcode %}
{% endtab %}
{% endtabs %}

4\. In the Script Editor toolbar, click Run the Script ▶︎.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1600263377000.png)

:blue\_book: **Note:** The script above applies the text formatting last used in Pixelmator Pro but you can further customize it by adding additional statements, such as defining the property values of the text size, font, or color.

You can go as simple or as complex as you want with your scripts, adding different new layers, shapes, and effects. For instance, you can download this example script to transform the simple "Hello, world!" script into an eye-catching graphic below:

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1599042228000.png)

If you'd like to learn more about scripting, check out our tutorial on [advanced automation and scripting with AppleScript](https://pixelmator.com/tutorials/resources/advanced-automation-and-scripting-with-applescript/).

***

### Batch process images using the Automator app

Automator is a great tool even for complete beginners as it offers a quick and easy approach to automation. It doesn't require any actual coding — you simply pick one or more of the pre-made Pixelmator Pro actions, add them to a workflow, and run it. You can also create Quick Actions, folder actions, or save individual workflows to use in the future.

![](https://help.pixelmator.com/pixelmator-pro/3.5/assets/English/1599657323000.jpeg)

There are currently 9 different Pixelmator Pro actions you can find in Automator:

* _Auto White Balance Images_: Automatically corrects the white balance of photos using the White Balance feature of Pixelmator Pro.
* _Apply Color Adjustments to Images_: Applies the selected Pixelmator Pro color adjustment preset to images.
* _Change Type of Images_: Converts the image file type from one format to another.
* _Increase Resolution of Images_: Increases the resolution of images by 3 times using the Super Resolution algorithm.
* _Trim Images_: Deletes transparent or solid colored areas from the edges of images.
* _Auto Enhance Image_: Automatically enhances photos, balancing colors and improving exposure, using the ML Enhance feature of Pixelmator Pro.
* _Apply Effects to Images_: Applies the selected Pixelmator Pro effect preset to images.
* _Denoise Images_: Automatically removes camera noise from images using the Denoise algorithm.
* _Scale Images_: Resizes the images passed to it, either proportionally or freely.

See our tutorial on [batch processing images with Pixelmator Pro](https://www.pixelmator.com/tutorials/resources/batch-process-images-with-pixelmator-pro/) to learn more about working with Automator.
