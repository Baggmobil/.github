# Adding Baggmobil NuGet references to your solution
  
Some projects are built as NuGet packages in the **Baggmobil** soultion and this document provides a step-by-step guide on how to add these NuGet package references to your solution.

Once you clone any [Baggmobile repository](https://github.com/orgs/Baggmobil/repositories) and open it on Visual Studio, the IDE will report an error saying unable to find the NuGet packages *Baggmobil.Framework.Common* and *Baggmobil.Framework.Telemetry* (or any other newer NuGets). The error is characterized by a yellow exclamation mark beside the package name in the *Visual Studio's Solution Explorer* as seen in screenshot below.

![NuGet Error](https://github.com/Baggmobil/.github/blob/master/images/Baggmobil%20NuGet%20error.jpeg)

## Steps
1. In *Visual Studio*, under *Tools* menu select *Options*.
2. From the pop-up menu that opens, select *NuGet Package Manager* > *Package Sources* from the menu options on the left side.

<img src="https://github.com/Baggmobil/.github/blob/master/images/VS%20options%20NuGet%20Sources.png" width="50%" />

3. Click on the green add icon on the top right corner of *Options* the pop-up window.
4. Enter the following details:
    - Name: Baggmobil
    - Source: https://nuget.pkg.github.com/Baggmobil/index.json
5. Click the *OK* button to apply the changes and close the *Options* the pop-up window.
6. Rebuild your solution. You will get a prompt requesting for credentials.
7. 
