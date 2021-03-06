---
old_url: properties.htm
title: "Properties"
active_menu_item: developers
class_name: developers
full_width: true
---


<table>
<tr>
<td width="172">
<a id="general"> </a> <b>General</b>

</td>
<td width="21">
</td>
<td width="754">
</td>
</tr>
<tr>
<td width="148">
Widget Class

</td>
<td width="21">
</td>
<td width="754">
Internal class name of the widget. - MediaElementAudio / MediaElementVideo

</td>
</tr>
<tr>
<td width="172">
Name

</td>
<td width="21">
</td>
<td width="754">
This is the Widget name that is displayed when references are made to the Widget. You can choose any name that includes alphanumeric characters.

</td>
</tr>
<tr>
<td width="172">
Source

</td>
<td width="21">
</td>
<td width="754">
Specify the URL or Resource to load the video from

</td>
</tr>
<tr>
<td width="172">
Poster

</td>
<td width="21">
</td>
<td width="754">
The image to display when the video has not been started

</td>
</tr>
<tr>
<td width="172">
Autoplay

</td>
<td width="21">
</td>
<td width="754">
Play the video when the page is displayed

</td>
</tr>
<tr>
<td width="172">
Controls

</td>
<td width="21">
</td>
<td width="754">
Use the Widget's in-built video controls

</td>
</tr>
<tr>
<td width="172">
Preload

</td>
<td width="21">
</td>
<td width="754">
Determines whether the video should be preloaded (not YouTube)

</td>
</tr>
<tr>
<td width="172">
Volume

</td>
<td width="21">
</td>
<td width="754">
The default volume level

</td>
</tr>
</table>
<table>
<tr>
<td width="172">
<a id="layout"> </a> <b>Layout</b>

</td>
<td width="21">
</td>
<td width="754">
</td>
</tr>
<tr>
<td width="172">
X

</td>
<td width="21">
</td>
<td width="754">
Number of pixels from the left edge of the Page.

</td>
</tr>
<tr>
<td width="172">
Y

</td>
<td width="21">
</td>
<td width="754">
Number of pixels from the top edge of the Page.

</td>
</tr>
<tr>
<td width="172">
Sizes

</td>
<td width="21">
</td>
<td width="754">
  Where you can set the Width and Height of the widget. If a widget is within a Container in Vertical or Horizontal mode, then the widget can also be made to change size in response to the size of the display width and height See <a href="/developers/documentation/product-guide/content-and-app-layout/responsive-adaptive-fluid-design/sizes-property-dialog">'Sizes' Property Dialog</a>

</td>
</tr>
<tr>
<td width="172">
Repeat

</td>
<td width="21">
</td>
<td width="754">
  Find out more about this in <a href="/developers/documentation/product-guide/content-and-app-layout/editing-and-laying-out-reference/repeating-widgets-across-multi">Repeating Widgets Across Multiple Pages</a> .

</td>
</tr>
<tr>
<td width="172">
Z-Index

</td>
<td width="21">
</td>
<td width="754">
A number that indicates the imaginary layer that the Widget is in. If you imagine several Widgets all placed over one another, the top-most Widget has the highest Z-Index and the bottom most Widget has the lowest. You can adjust the Z-Index by changing the value. You can also use the right-click menu to adjust these in a friendlier way.

</td>
</tr>
<tr>
<td width="172">
Anchors

</td>
<td width="21">
</td>
<td width="754">
  This is used in conjunction with "Docked" App Pages. You can use this to allows a Widget's X, Y, Width and Height to be automatically altered as the browser window is resized. See <a href="/developers/documentation/product-guide/content-and-app-layout/editing-and-laying-out-reference/widget-anchoring">Docking & Anchoring</a> .

</td>
</tr>
<tr>
<td width="172">
Align in Container

</td>
<td width="21">
</td>
<td width="754">
Left/Center/Right. Set as required to align the widget within its parent container

</td>
</tr>

</table>
<table>
<tr>
<td width="172">
<a id="behavior"> </a> <b>Behavior</b>

</td>
<td width="21">
</td>
<td width="754">
</td>
</tr>
<tr>
<td width="172">
Drag and Drop

</td>
<td width="21">
</td>
<td width="754">
If set to true, the user is able to drag and drop the widget with the mouse at run time

</td>
</tr>
<tr>
<td width="172">
Resizing

</td>
<td width="21">
</td>
<td width="754">
Disable/Enable. Set to True to allow the widget to be resized at Runtime. Configurable Max/Min Width and Height, Right & Bottom, Top & Left or All

</td>
</tr>
<tr>
<td width="172">
Visible

</td>
<td width="21">
</td>
<td width="754">
Set to False if you want the Widget to appear hidden by default. You would use Javascript to override this at a later stage.

</td>
</tr>
<tr>
<td width="172">
Enable

</td>
<td width="21">
</td>
<td width="754">
Set to false to leave the Widget visible but to prevent any user interaction

</td>
</tr>

</table>
<table>
<tr>
<td width="172">
<a id="data"> </a> <b>Data</b>

</td>
<td width="21">
</td>
<td width="754">
Not currently supported

</td>
</tr>

</table>
<table>
<tr>
<td width="174">
<a id="style"> </a> <b>Style</b>

</td>
<td width="20">
</td>
<td width="748">
</td>
</tr>
<tr>
<td width="174">
Opacity

</td>
<td width="20">
</td>
<td width="748">
This % value specifies the transparency of the Widget.

</td>
</tr>
<tr>
<td width="174">
Margin

</td>
<td width="20">
</td>
<td width="748">
  Used to specify the margin around a widget when the parent container is in Relative Mode. See <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/setting-a-margin">Setting a Margin</a>

</td>
</tr>
<tr>
<td width="174">
Border

</td>
<td width="20">
</td>
<td width="748">
Controls Border for whole container, using Border dialog

</td>
</tr>
<tr>
<td width="174">
BG Color

</td>
<td width="20">
</td>
<td width="748">
Set the background color of the Widget.

</td>
</tr>
</table>

## See Also

- [YouTube Widget](/developers/documentation/product-guide/widget-properties-events/advanced/youtube/)
- [jPlayer Widget](/developers/documentation/product-guide/widget-properties-events/advanced/jplayer/)
