# Gosso.EPiServerAddOn.ContextMenu.OpenInFormsView 
**version 1.0.2 (2017-11-22)**

[![Platform](https://img.shields.io/badge/Episerver-%208.0+-orange.svg?style=flat)](http://world.episerver.com/cms/) [![Platform](https://img.shields.io/badge/Episerver-%2010.0-green.svg?style=flat)](http://world.episerver.com/cms/) [![Platform](https://img.shields.io/badge/Episerver-%2011.1-green.svg?style=flat)](http://world.episerver.com/cms/)

An Episerver addon that adds a command to the page tree that opens the content in forms view.

![alt text](https://raw.githubusercontent.com/LucGosso/Gosso.EPiServerAddOn.ContextMenu.OpenInFormsView/master/OpenInFormsView.png "This is the Context menu on the tree")

Also check out these AddOn on same theme:  
https://github.com/episerver/AddOn.ReloadChildren   
https://github.com/mariajemaria/ContextMenuOpenInNewTab  

# Installation

.1 - You can find it on Nuget.episerver.com: http://nuget.episerver.com/en/OtherPages/Package/?packageId=Gosso.EPiServerAddOn.ContextMenu.OpenInFormsView

.2 - There is a nuget package available under the releases tab. This can be installed via the package manager console in Visual Studio.

Put it in your local nuget feed, Run "install-package Gosso.EPiServerAddOn.ContextMenu.OpenInFormsView" in package manager console.

The files will be saved into your module and modulesbin folders. And not referenced, not needed.

Troubleshooting with TFS: Remember to check in files under "modules" and "modulesbin". If you have problems in build/dev servers with local packages, and you dont have a local nuget server, a work around is to remove the row in packages.config. (Or Check in the package)

