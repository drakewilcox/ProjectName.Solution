# _TEMPLATE_

#### _C# PROJECT TEMPLATE_, _Mar. 3, 2020_

#### By _**Drake Wilcox**_

## Description

_This is a template for future projects in C# to make project setup streamlined. To use this for a new project. Rename all files that contain 'Project Name' and "Class Name," and and make sure the ProjectName is changed in the 'ProjectName.Tests.csproj' file. Remove any git files by typing ``rm -rf .git`` in the terminal and re-initialize git by typing ``git init`` in the terminal. To create the 'bin' and 'obj' folders and run tests navigate to the "ProjectName.Tests" folder and type ``dotnet restore`` in your terminal. To begin testing type ``dotnet test`` in the terminal._

## Specifications:

| Specification | Example Input | Example Output |
| :-------------:|:-------------:|:-------------:|
| When the user does this, the application will do that | "Input to test" | "Expected output to test" |

## Setup/Installation Requirements

To use this application, follow the following instructions. 

#### Installing .NET core

##### For macOS: 

* Dowload [this .NET Core SDK](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.106-macos-x64-installer) which will prompt a .pkg file download from Microsoft.

* Open the file. This will launch and walk you through installation steps. Use default settings. 

* Confirm the installation is successful by opening the terminal and running the command ``$ dotnet --version``. You should see something like ``2.2.105`` in response.

##### For Windows: 
* Visit the [Microsoft .NET Installation Guide](https://docs.microsoft.com/en-us/dotnet/framework/install/).

#### Installing donet script

* After installing .NET Core, run the command `` dotnet tool install -g dotnet-script `` in Terminal. 

#### Application Setup:
_Clone this repository via Terminal using the following commands:_
* ``$ cd desktop``
* ``$ git clone "repository link" ``
* ``$ cd ProjectName.Solution``

_To Run this Console Application, enter the following command in the Terminal:_

* ``$ dotnet run``

_To view the source code of this application, open the folder in the Text Editor of your choice. (Example: to open via Visual Code enter the command ``code . `` in Terminal.)_

## Technologies Used
* _Git_
* _C#_
* _.NET Core 2.2_
* _dotnet script_
* _VS Code_

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2020 **_Drake Wilcox_**