---
title: ToggleButton Object
page_title: ToggleButton Object - RadToggleButton
description: Check our Web Forms article about ToggleButton Object.
slug: togglebutton/client-side-programming/togglebutton-object
tags: togglebutton,object
published: True
position: 1
---

# ToggleButton Object

The following table lists the most important members of the client-side RadToggleButton object:

>caption Public Properties

| Name | Description |
| ------ | ------ |
| **get_enabled** |Returns a value indicating whether the button control is enabled.|
| **set_enabled** |Sets whether the button is enabled.|
| **get_text** |The text displayed in the RadToggleButton control.|
| **set_text** |Sets the text displayed in the RadToggleButton control.|
| **get_toolTip** |Gets the text displayed when the mouse pointer hovers over the RadToggleButton control.|
| **set_toolTip** |Sets the text displayed when the mouse pointer hovers over the RadToggleButton control.|
| **get_uniqueID** |Gets the unique, hierarchically qualified identifier for the RadToggleButton control.|
| **get_iconElement** |Gets a reference to the HTML element that holds the icon.|
| **get_textElement** |Gets a reference to the HTML element that holds the text of the RadToggleButton control.|
| **get_cssClass** |Gets the Cascading Style Sheet (CSS) class rendered by the RadToggleButton control on the client.|
| **get_disabledCssClass** |Gets the CSS class applied when the control is disabled.|
| **get_hoveredCssClass** |Gets the CSS class applied to the RadToggleButton control when the mouse pointer is over the control.|
| **get_pressedCssClass** |Gets the CSS class applied to the RadToggleButton control when the control is pressed.|
| **get_commandName** |Gets the command name associated with the RadToggleButton control that is passed to the Command event.|
| **set_commandName** |Sets the command name associated with the RadToggleButton control that is passed to the Command event.|
| **get_commandArgument** |Gets an optional parameter passed to the Command event along with the associated CommandName.|
| **set_commandArgument** |Sets an optional parameter passed to the Command event along with the associated CommandName.|
| **get_autoPostBack** |Gets a bool value indicating whether the RadToggleButton control automatically posts back to the server when clicked.|
| **set_autoPostBack** |Sets or sets a bool value indicating whether the RadToggleButton control automatically posts back to the server when clicked.|
| **get_height** |Gets the height of the RadToggleButton control.|
| **get_width** |Gets the width of the RadToggleButton control.|
| **IsInputTypeSubmit** |Gets a bool value indicating whether the button is a submit button.|
| **get_singleClick** |Gets a bool value indicating whether the RadToggleButton control will be immediately disabled after the user has clicked it (i.e., enables/disables "Single Click" functionality).|
| **get_singleClickText** |Gets the text displayed in the RadToggleButton control after the button is clicked and disabled (i.e. the text used for the 'Single Click' functionality).|
| **enableAfterSingleClick** |Enables the button and restores the button's text, after it has been disabled by a single click.|
| **get_visible** |Gets a bool value indicating whether the button is visible.|
| **set_visible** |Shows/hides the button.|
| **get_validationGroup** |Gets the name of the ValidationGroup to which RadToggleButton is assigned.|
| **set_validationGroup** |Sets the ValidationGroup to which RadToggleButton should be assigned.|
|**get_toggleStates**|Gets the collection of ButtonToggleState objects that belong to the RadToggleButton control.|
|**set_toggleStates**|Sets the collection of ButtonToggleState objects that belong to the RadToggleButton control.|
|**get_selectedToggleState**| Gets the currently selected ToggleState of the RadToggleButton control.|
|**set_selectedToggleState**| Sets the currently selected ToggleState of the RadToggleButton control.|
|**get_selectedToggleStateIndex**| Gets the index of the currently selected ToggleState of the RadToggleButton control.|
|**set_selectedToggleStateIndex**| Sets the index of the currently selected ToggleState of the RadToggleButton control.|

>caption Public Methods

| Name | Description |
| ------ | ------ |
| **focus** |Brings the focus to the RadToggleButton control.|
| **click** |Executes a programmatic button click. Accepts an optional boolean parameter that specifies whether the client-side [clicking event]({%slug togglebutton/client-side-programming/events/onclientclicking%}) of RadToggleButton will be fired when the control is clicked programmatically. If the function is called without parameter,	the clicking event will not be fired.|

>caption Public Properties of **RadButtonToggleState** object.

| Properties | Description |
| ------ | ------ |
| **get_index()** |Gets the 0-based index of the ToggleState object in the ToggleStates collection.|
| **get_text()** |Gets the text displayed in the ButtonToggleState control.|
| **get_cssClass()** |Gets the CSS class applied to the ButtonToggleState object.|
| **get_hoveredCssClass()** |Gets the CSS class applied to the ButtonToggleState object when the mouse pointer is over the control.|
| **get_pressedCssClass()** |Gets the CSS class applied to the ButtonToggleState object when the control is pressed.|
| **get_height()** |Gets the height of the ButtonToggleState object.|
| **get_width()** |Gets the width of the ButtonToggleState object.|
| **get_primaryIconCssClass()** |Gets the CSS class applied to the Icon.|
| **get_primaryIconUrl()** |Gets the URL to the image used as the Icon.|
| **get_primaryHoveredIconUrl()** |Gets the URL to the image showed when the ButtonToggleState is hovered.|
| **get_primaryPressedIconUrl()** |Gets the URL to the image showed when the ButtonToggleState is pressed.|
| **get_primaryIconHeight()** |Gets the height of the Icon.|
| **get_primaryIconWidth()** |Gets the width of the Icon.|
| **get_primaryIconTop()** |Gets the top edge of the Icon, relative to the ButtonToggleState object's wrapper element.|
| **get_primaryIconLeft()** |Gets the left edge of the Icon, relative to the ButtonToggleState object's wrapper element.|
| **get_imageUrl()** |Gets the location of an image to display in the ButtonToggleState object.|
| **get_hoveredImageUrl()** |Gets the location of an image to display in the ButtonToggleState object, when the mouse pointer is over the control.|
| **get_pressedImageUrl()** |Gets the location of an image to display in the ButtonToggleState object, when the control is pressed.|

>caption Methods for modifying client-side event handlers dynamically

| Name | Description |
| ------ | ------ |
| **add_load** |The name of the JavaScript function called when the control loads.|
| **remove_load** |Removes a handler for the load event.|
| **add_clicking** |The name of the JavaScript function called when the RadToggleButton control is clicked.|
| **remove_clicking** |Removes a handler for the clicking event.|
| **add_toggleStateChanging** |The name of the JavaScript function called before the state of the ToggleButton is changed.|
| **remove_toggleStateChanging** |Removes a handler for the toggleStateChanging event.|
| **add_toggleStateChanged** |The name of the JavaScript function called when the state of the ToggleButton is changed.|
| **remove_toggleStateChanged** |Removes a handler for the toggleStateChanged event.|
| **add_clicked** |The name of the JavaScript function called when the RadToggleButton control is clicked.|
| **remove_clicked** |Removes a handler for the clicked event.|
| **add_mouseOver** |The name of the JavaScript function called when the mouse hovers over the control.|
| **remove_mouseOver** |Removes a handler for the mouseOver event.|
| **add_mouseOut** |The name of the JavaScript function when the mouse leaves the control.|
| **remove_mouseOut** |Removes a handler for the mouseOut event.|

You can read more on the subject in the [Setting Client Event Handlers by Using JavaScript]({%slug togglebutton/client-side-programming/events/setting-event-handlers-via-javascript%}) help article.

## See Also

 * [Client-side Programming Overview]({%slug togglebutton/client-side-programming/overview%})
 
