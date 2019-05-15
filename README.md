# Power Inspector Documentation
Version 0.9.0b

## Introduction

### What Is Power Inspector?

Most plugins that alter the Inspector, do it by slipping in small changes to the Default Inspector window, and slightly tweaking things at the **field** or **Component level**.

Power Inspector, on the other hand, is a **full-on replacement** for the Default Inspector window.

Remaking the Inspector from the ground up with Power Inspector has made it possible to not only change how fields and Components look like, but to completely reimagine the whole Inspector experience.

The aim with Power Inspector has been to fully incorporate the basic feature set that you have come to expect from the Default Inspector, and then to keep improving upon that foundation, with the goal of speeding up your workflow and providing the necessary tools to avoid common pain points.

### Decoupled Design

A **core ambition** with Power Inspector has been to keep it as **decoupled from your code** as possible, to give you access to as many features as possible, with **zero** modification of your code.
You do not need to inherit from any base class.
You do not need to add lots of attributes to your code.
You just open up the Power Inspector window and you're good to go.

The Default Inspector window, should you ever need it, will also always remain in its original state and fully usable alongside Power Inspector.

This all ensures that the risk of integration is minimal.


## Installation

### Supported Unity Versions

Power Inspector supports Unity version **5.6.7f1 and newer**.
The latest version of Unity tested to be working is **2019.1.0f2** (newer versions might work also).

**Beta** versions of Unity are not officially supported, so use Power Inspector with them at your own risk.

### How To Install

Installing Power Inspector is done using the Asset Store window inside of Unity.
Open the Asset Store window using the menu item **Window > Asset Store**.
Find the listing for Power Inspector in **My Assets**.
Click the **Download** button, then wait for the download to finish. If you don’t see a Download button next to the asset listing, you can **move on to the next step**.
Click **Import** and wait until the loading bar disappears and the **“Import Unity Package” dialog** opens.
Click **Import**, then wait until the loading bar disappears. You should **not** change what items are ticked on the window, unless you know what you’re doing, because that could mess up the installation.
If you see a dialog prompt about performing an **API Update**, click the button labeled “**I made backup. Go ahead!**”

Power Inspector should now be installed and all **ready to use**!

If you run into any issues during installation, please refer to the Troubleshooting page.

To learn how start using Power Inspector, refer to teh Getting Started page.

## Updating

You might want to check from time to time if Power Inspector has new updates, so you don’t miss out on new features, and so that you get all the latest fixes for the latest Unity version.

Updating Power Inspector is very similar to installing it, and done using the Asset Store window inside of Unity.

### Checking For Updates
1.  Open the Asset Store window using the menu item Window \> Asset Store.
2.  Find the listing for Power Inspector in My Assets.
3.  If you see a button labeled “Import”, that means that your installation of Power Inspector is up-to-date, and you are done. If you see a button labeled “Update”, continue to the next step to update Power Inspector to the latest version.
4.  Click the Update button, then wait for the download to finish.
5.  Click Import and wait until the loading bar disappears and the “Import Unity Package” dialog opens.
6.  Click Import, then wait until the loading bar disappers. You should NOT tick or untick any items in the list, unless you know what you’re doing, because that could mess up the installation.
7.  If you see a dialog prompt about performing an API Update, click the button labeled “I made backup. Go ahead!”

Power Inspector is now updated to the latest version.

If you see any errors, refer to the Installation Troubleshooting page.
If you’re still having problems after that, please contact us via the email address support@sisus.co.


## Getting Started

### Opening The Power Inspector Window

Use the menu item **Window > General > Power Inspector** to open the Power Inspector Window.
You can also open a new Power Inspector window using the keyboard shortcut **Ctrl+Shift+T **(**Cmd+Shift+T** on macOS).

![](https://docs.sisus.co/wp-content/uploads/2019/04/OpeningPowerInspector.png)

**Note:** it is possible to open multiple instances of the Power Inspector window.

### Using The Power Inspector Window

In terms of the basics, you use the Power Inspector window like you would use the Default Inspector: when you **select** Unity Objects in the **Hierarchy** window or the **Project** window, their **data is displayed** in the Inspector View, where you can view and edit it.

There are then a multitude of enhancements that Power Inspector adds on top of the basic feature set. Read through the Feature pages to **learn** all about those enhancements, and unlock the **full potential** of Power Inspector.

## List of Main Features

### Navigation Buttons
New navigation buttons allow you to easily jump between previously inspected targets.
[read more](https://docs.sisus.co/power-inspector/features/navigation-buttons/)

### Filter Field
Quickly find any field in the inspector using its name, type or value.
[read more](https://docs.sisus.co/power-inspector/features/filter-field/)

### Split View
Split the inspector into two parts with the press of a button, and view two different targets right next to each other.
[read more](https://docs.sisus.co/power-inspector/features/split-view-2/)

### Full-Fledged Keyboard Support
Arrow keys move field focus in an intuitive manner, and several new quick navigation options help you get around with speed.
[read more](https://docs.sisus.co/power-inspector/features/keyboard-navigation/)

### Dynamic Prefix Column
Automatically optimized prefixes column widths maximize the space you have to work with.
[read more](https://docs.sisus.co/power-inspector/features/dynamic-prefix-column/)

### Copy-Paste
Powerful cross-project copy-paste that works across different types.
[read more](https://docs.sisus.co/power-inspector/features/copy-paste/)

### Debug Mode+
Easily gain access to all fields, properties and methods of Components - including non-serialized and hidden ones.
[read more](https://docs.sisus.co/power-inspector/features/debug-mode/)

### Quick Invoke Menu
Easily invoke methods on Unity Objects via a dedicated header button.
[read more](https://docs.sisus.co/power-inspector/features/15-quick-invoke-menu/)