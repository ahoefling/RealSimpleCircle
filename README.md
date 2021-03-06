# Real Simple Circle's for Xamarin.Forms
A real simple circle component built for Xamarin.Forms

## Setup

* Available on NuGet: [![NuGet](https://img.shields.io/nuget/v/RealSimpleCircle.svg?label=NuGet)](https://www.nuget.org/packages/RealSimpleCircle)
* Install into your PCL/.NET Standard and Client Projects

## Build

* [![Build status](https://ci.appveyor.com/api/projects/status/d0frm6gffguiclpy?svg=true)](https://ci.appveyor.com/project/ahoefling/realsimplecircle)
* CI NuGet Feed: [https://ci.appveyor.com/nuget/realsimplecircle](https://ci.appveyor.com/nuget/realsimplecircle)
    
### Platform Support
RealSimpleCircle is available for use in the following supported platforms.

| Platform         | Supported | Version     |
|------------------|-----------|-------------|
| Xamarin.Android  | Yes       | API 23 +    |
| Xamarin.iOS      | Yes       | iOS 10 +    |
| NetStandard	   | Yes       | 1.0 +		 |


## Usage ##

### C# ###
#### iOS and Android####
Initialize the renderer in the AppDelegate (iOS) and MainActivity (Android)

```c#
Xamarin.Forms.Init();
CircleRenderer.Init();
```

### XAML: ###
Add the namespace in the xmlns:

```xml
xmlns:controls="clr-namespace:RealSimpleCircle.Abstractions;assembly=RealSimpleCircle.Abstractions"
```

Add the control:

```xml
<controls:Circle FillColor="Black"
                 StrokeColor="Red"
                 Active="True" />
```

## Bindable Properties

| Property    | Description                                                        | Default Value              |
|-------------|--------------------------------------------------------------------|----------------------------|
| FillColor   | Gets or Sets the fill color for the circle.                        | `Color.Black`              |
| StrokeColor | Gets or Sets the circle border color                               | `Color.Black`              |
| Active      | Gets or Sets if the circle fill color is visible or not            | `False`                    |

## Created By: [@Andrew_Hoefling](https://twitter.com/andrew_hoefling)

* Twitter: [@Andrew_Hoefling](https://twitter.com/andrew_hoefling)
* Blog: [andrewhoefling.com](http://www.andrewhoefling.com)

## History
I have worked on many Xamarin.Forms projects where I needed a really simple circle renderer. I always found myself searching the forums 
for code snippets or copying code snippets from other projects. I decided this could be a valuable simple control to share with the community
on NuGet.

### License

The MIT License (MIT) see License File