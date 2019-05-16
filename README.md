![](https://docs.sisus.co/wp-content/uploads/2019/05/Title.png)

<p align="center">
	<a href="https://docs.sisus.co/power-inspector/">
		<img src="https://docs.sisus.co/wp-content/uploads/2019/01/Documentation.png" alt="Online Documentation">
	</a>
	<a href="http://u3d.as/1sNc">
		<img src="https://docs.sisus.co/wp-content/uploads/2019/01/UnityAssetStore.png" alt="Unity Asset Store">
	</a>
</p>

# Introduction

### What Is Power Inspector?

Power Inspector is a feature-packed [inspector window](https://docs.unity3d.com/Manual/UsingTheInspector.html) alternative for [Unity](https://unity3d.com/unity).

Most plugins that alter the inspector, do it by slipping in small changes to the default inspector window, and slightly tweaking things at the **field** or **Component level**.

Power Inspector, on the other hand, is a **full-on replacement** for the default inspector window.

Remaking the inspector from the ground up with Power Inspector has made it possible to not only change how fields and Components look like, but to completely **reimagine** the whole inspector experience.

The aim with Power Inspector has been to fully incorporate the basic feature set that you have come to expect from the default inspector, and then to keep improving upon that foundation, with the goal of **speeding up your workflow** and providing the necessary tools to **avoid common pain points**.

### Decoupled Design

A **core ambition** with Power Inspector has been to keep it as **decoupled from your code** as possible, to give you access to as many features as possible without requiring any modifications to code. You do **not** need to inherit from any **base classes**, and you do not need to add **any attributes** to your code; just open up the Power Inspector window and you're good to go.

The default inspector window, should you ever need it, will also always remain in its original state and fully usable alongside Power Inspector.

This all ensures that the **risk** of integration is **minimal**.

# Main Features

![](https://docs.sisus.co/wp-content/uploads/2019/05/features.png)

#### Navigation Buttons
New navigation buttons allow you to easily jump between previously inspected targets.
[read more](https://docs.sisus.co/power-inspector/features/navigation-buttons/)

#### Filter Field
Quickly find any field in the inspector using its name, type or value.
[read more](https://docs.sisus.co/power-inspector/features/filter-field/)

#### Split View
Split the inspector into two parts with the press of a button, and view two different targets right next to each other.
[read more](https://docs.sisus.co/power-inspector/features/split-view/)

#### Full-Fledged Keyboard Support
Arrow keys move field focus in an intuitive manner, and several new quick navigation options help you get around with speed.
[read more](https://docs.sisus.co/power-inspector/features/keyboard-navigation/)

#### Dynamic Prefix Column
Automatically optimized prefixes column widths maximize the space you have to work with.
[read more](https://docs.sisus.co/power-inspector/features/dynamic-prefix-column/)

#### Copy-Paste
Powerful cross-project copy-paste that works across different types.
[read more](https://docs.sisus.co/power-inspector/features/copy-paste/)

#### Debug Mode+
Easily gain access to all fields, properties and methods of Components - including non-serialized and hidden ones.
[read more](https://docs.sisus.co/power-inspector/features/debug-mode/)

#### Quick Invoke Menu
Easily invoke methods on Unity Objects via a dedicated header button.
[read more](https://docs.sisus.co/power-inspector/features/quick-invoke-menu/)

You can find the [full list of features](https://docs.sisus.co/power-inspector/category/features/) in the online documentation.

# Installation

### Where To Get

Power Inspector can be purchased from the [Unity Asset Store](http://u3d.as/1sNc).

### How To Install

Installing Power Inspector is done using the Asset Store window inside of Unity.
1.  Open the Asset Store window using the menu item Window \> Asset Store.
2.  Find the listing for Power Inspector in My Assets.
3.  Click the Download button, then wait for the download to finish. If you don’t see a Download button next to the asset listing, you can move on to the next step.
4.  Click Import and wait until the loading bar disappears and the “Import Unity Package” dialog opens.
5.  Click Import, then wait until the loading bar disappears. You should not change what items are ticked on the window, unless you know what you’re doing, because that could mess up the installation.
6.  If you see a dialog prompt about performing an API Update, click the button labeled “I made backup. Go ahead!”

### Supported Unity Versions

Power Inspector supports Unity version **5.6.7f1 and newer**.
The latest version of Unity tested to be working is **2019.1.0f2** (newer versions might work also).

**Beta** versions of Unity are not officially supported, so use Power Inspector with them at your own risk.

# Getting Started

### Opening The Power Inspector Window

Use the menu item **Window > General > Power Inspector** to open the Power Inspector Window.
You can also open a new Power Inspector window using the keyboard shortcut **Ctrl+Shift+T** (**Cmd+Shift+T** on macOS).

![](https://docs.sisus.co/wp-content/uploads/2019/04/OpeningPowerInspector.png)

**Note:** it is possible to open multiple instances of the Power Inspector window.

### Using The Power Inspector Window

In terms of the basics, you use the Power Inspector window like you would use the default inspector: when you **select** Unity Objects in the **Hierarchy** window or the **Project** window, their **data is displayed** in the inspector view, where you can view and edit it.

For more information refer to the [full online documentation](https://docs.sisus.co/power-inspector).