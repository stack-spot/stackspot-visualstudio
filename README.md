# StackSpot Extension for Visual Studio 2022

## **Table of contents**

### 1. [**About**](#about)
### 2. [**Getting Started**](#getting-started)
>#### 2.1. [**Build Requirements**](#build-requirements)
>#### 2.2. [**Compile and debug**](#compile-and-debug)
### 3. [**Installation**](#installation)
### 4. [**Usage**](#usage)
### 5. [**Documentation**](#documentation)
### 6. [**Contributing**](#contributing)
### 7. [**Code of Conduct**](#code-of-conduct)
### 8. [**License**](#license)
### 9. [**Other Information**](#other-information)
>#### 9.1. [**Visual Studio extension development documentation**](#visual-studio-extension-development-documentation)

## **About**

**StackSpot Extension for Visual Studio 2022** is an extension that extends [STK CLI](https://docs.stackspot.com/latest/docs/stk-cli/) to MS Visual Studio 2022 and allows you to import stacks, create a StackSpot project, apply plugins, and many more features. But all this is inside of your favorite IDE.

## **Getting started**

### **Build Requirements**

- [Visual Studio 2022 (Any versions)](https://visualstudio.microsoft.com/pt-br/downloads/)
- [.NET Framework 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- [Visual Studio SDK](https://learn.microsoft.com/en-us/visualstudio/extensibility/installing-the-visual-studio-sdk?view=vs-2022)

### **Compile and debug**

You can download or clone this repository to debug and test this extension using experimental instance of Visual Studio, just opening the solution and start the debug mode (F5) using StackSpot.VisualStudio project as Startup Project.

## **Installation**

We will let this extension available in Visual Studio Marketplace, but if you want to install through the VSIX file check this:
[Install without using the Manage Extensions dialog box](https://learn.microsoft.com/en-us/visualstudio/ide/finding-and-using-visual-studio-extensions?view=vs-2022#install-without-using-the-manage-extensions-dialog-box)

## **Usage**

Updating CLI:

<a href="https://github.com/stack-spot/stackspot-visualstudio-extension/raw/main/images/UpdatingCLI.gif" target="_blank"><img src="https://github.com/stack-spot/stackspot-visualstudio-extension/blob/main/images/UpdatingCLI.gif" alt="Gif showing how to update CLI using StackSpot Extension for Visual Studio 2022" border="0" /></a>

Importing stack:

<a href="https://github.com/stack-spot/stackspot-visualstudio-extension/raw/main/images/ImportStack.gif" target="_blank"><img src="https://github.com/stack-spot/stackspot-visualstudio-extension/blob/main/images/ImportStack.gif" alt="Gif showing how to import stack using StackSpot Extension for Visual Studio 2022" border="0" /></a>

Creating a new project:

<a href="https://github.com/stack-spot/stackspot-visualstudio-extension/raw/main/images/CreateProject.gif" target="_blank"><img src="https://github.com/stack-spot/stackspot-visualstudio-extension/blob/main/images/CreateProject.gif" alt="Gif showing how to create a new project using StackSpot Extension for Visual Studio 2022" border="0" /></a>

Aplying plugin:

<a href="https://github.com/stack-spot/stackspot-visualstudio-extension/raw/main/images/ApplyPlugin.gif" target="_blank"><img src="https://github.com/stack-spot/stackspot-visualstudio-extension/blob/main/images/ApplyPlugin.gif" alt="Gif showing how to apply plugin using StackSpot Extension for Visual Studio 2022" border="0" /></a>

## **Documentation**

Check our official documentation page to use StackSpot Extension for Visual Studio 2022:
[Documentation link](https://docs.stackspot.com/latest/docs/extensions-for-ide/visualstudio/)

## **Contributing**

Check out our [**Contributing Guide**](https://github.com/stack-spot/stackspot-visualstudio-extension/blob/main/CONTRIBUTING.md) to learn about our development process, how to suggest bug fixes and improvements.

Check out other guides:

- [**Security**](https://github.com/stack-spot/stackspot-visualstudio-extension/blob/main/SECURITY.md)

- [**Developer Guide**](https://github.com/stack-spot/stackspot-visualstudio-extension/blob/main/DEVELOPER_GUIDE.md)

## **Code of Conduct**
Please follow the [**Code of Conduct**](https://github.com/stack-spot/stackspot-visualstudio-extension/blob/main/CODE_OF_CONDUCT.md) in all your interactions with our project.

## **License**
[**Apache License 2.0**](https://github.com/stack-spot/stackspot-visualstudio-extension/blob/main/LICENSE).

## **Other information**

### **Visual Studio extension development documentation**

- https://learn.microsoft.com/en-us/visualstudio/extensibility/starting-to-develop-visual-studio-extensions?view=vs-2022