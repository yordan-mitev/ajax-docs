---
title: Render Modes
page_title: Render Modes - RadDataPager
description: Check our Web Forms article about Render Modes.
slug: datapager/mobile-support/render-modes
tags: render,modes
published: True
position: 2
---

# Render Modes



**RadDataPager** has three different render modes that can change the actual HTML markup that is rendered.Those render modes are exposed via the **RenderMode** property that accepts the following values -**Classic**, **Mobile**, **Lightweight** and **Auto**.

The possible options are:

* **Classic** — this mode is the rendering that has been used before.It remains without changes and it is the default value of the property.	In this mode tables and background images (in several sprites) are used to create	the layout (including rounded corners and shadows).

* **Lightweight** — this mode is supported since **Q2 2015 Beta version** and emphasizes on semantic HTML and CSS3. It reduces the amount of markup the control renders	and makes it easier to customize. This also reduces the number of image sprites required by the control and the other controls from the suite it uses. In addition, all table elements are removed from the layout of the control.	All of this decreases the overall size and complexity of each skin, including custom ones.

* **Mobile** — this mode is supported since **Q2 2015 Beta** release	and with it, the control will change to create a user experience tailored to the device screen size.In this mode, **RadDataPager** is mobile-friendly and its touch zones are bigger and easier to select.

* **Auto** — this option will automatically decide how to render the control on a smart phone, tablet or PC and will switch	between **Classic** and **Mobile** render modes (depending on the used device).


## Setting Render Mode

There are two ways to configure the rendering mode of the controls:

* Setting the **RenderMode** property in the markup as a string, or setting it in the code-behind with a member	of the **Telerik.Web.UI.RenderMode** enum.Following is an example for setting the **RenderMode** property in the markup:

````ASP.NET
<telerik:RadDataPager ID="RadDataPager1" runat="server" RenderMode="Lightweight">
</telerik:RadDataPager>
````



* A **global setting in the web.config** file that will affect the entire application, unless a concrete value is specifiedfor a given control instance:

````ASP.NET
<appSettings>
	<add key="Telerik.Web.UI.DataPager.RenderMode" value="Lightweight" />
</appSettings>
````


