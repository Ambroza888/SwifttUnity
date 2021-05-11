# Launch a Unity Augmented Reality (AR) App from a SwiftUI iOS App.
Just for reference, I am using: Xcode version 12.5, Unity version: 2019.4.26f1
### [Limitations](https://docs.unity3d.com/Manual/UnityasaLibrary.html) of Using Unity as a Library in other applications
* Starting with **Unity 2019.3**, you can use Unity as a Library in other applications by integrating your content and the Unity runtime components in a native platform project. This enables you to embed content that uses 3D or 2D real-time rendering
, like AR
 experiences, interaction with 3D models, 2D mini-games, and so on. The Unity Runtime Library exposes ways to manage loading, activating, and unloading within the native application.
* Only full-screen rendering is supported. It’s not possible to render only on a part of the screen.
* When Unity is in an unloaded state (after calling ``Application.Unload``), it retains some amount of memory (between 80–180Mb) to be able to instantly switch back and run again in the same process. The amount of memory that is not released largely depends on the device’s graphics resolution.
* On iOS, if the Unity runtime quits entirely (after calling ``Application.Quit``), it’s not possible to reload Unity again in the same app session.
* You can’t load more than one instance of the Unity runtime, or integrate more than one Unity runtime.
* You might need to adapt your native and managed plug-ins
 to work properly.

 ## Create Unity AR app in Swift iOS App from scratch with Placenote SDK.
 To be able to use Augmented Reality in Unity we have to import 3rd party libary, SDK or plugins in Unity project(ex. Wikitude, Vuforiaand Placenote etc.)
### Create the iOS project
### Create the Unity project
### Connect Unity with iOS
### And now... some code!

![](Images/1.png)
