# Hololens Resources

I started this list as a personal reference for my own research. HoloLens is fairly new so apparently there's not much information available. Physical devices are rather limited so the developer community is small. But there are hidden gems out there, so please feel free to drop me a pull request if you find something useful, amazing or cool about HoloLens.

## Intro and setup

[https://www.ted.com/talks/alex_kipman_the_dawn_of_the_age_of_holograms](https://www.ted.com/talks/alex_kipman_the_dawn_of_the_age_of_holograms)  
Highly recommended. The creator of the HoloLens speaks about his vision for the future. This is also one of the very first moments the device is demoed before a live audience.

[https://www.microsoft.com/microsoft-hololens/en-us/developers](https://www.microsoft.com/microsoft-hololens/en-us/developers)  
A general introduction to the device. Have a look at the case studies and learn about the differences between AR (_Augmented Reality_), VR (_Virtual Reality_) and MR (_Mixed Reality_). The term MR is invented by Microsoft.

Some apps to try out before you start developing:  
- [Young Conker](https://www.microsoft.com/microsoft-hololens/en-us/apps/young-conker) : a game using your real environment;
- [RoboRaid](https://www.microsoft.com/microsoft-hololens/en-us/apps/RoboRaid) : shoot the aliens out of your own walls;
- [HoloTour](https://www.microsoft.com/microsoft-hololens/en-us/apps/HoloTour) : visit ancient Rome, this is in fact a pure VR application;
- [HoloStudio](https://www.microsoft.com/microsoft-hololens/en-us/apps/holostudio) : create virtual 3D objects.

[https://developer.microsoft.com/en-us/windows/holographic/install_the_tools](https://developer.microsoft.com/en-us/windows/holographic/install_the_tools)  
Installation instructies for HoloLens development. Remark: in order to run the emulator, you need to enable Hyper-V. So Windows 10 Home Edition does't qualify for development, only the Pro/Enterprise versions are suited.

## Some Tips and Tricks
[http://blog.galasoft.ch/posts/2016/05/my-hololens-101-notes/](http://blog.galasoft.ch/posts/2016/05/my-hololens-101-notes/)  
Some random notes from a programmer (Laurent Buignon, the creator of MVVM Light), taking his first HoloLens development steps.

[https://vbandi.net/2016/08/18/hololens-mixed-reality-streaming-done-right/](https://vbandi.net/2016/08/18/hololens-mixed-reality-streaming-done-right/)  
Interesting article with tips to create fluid video streams from your HoloLens. The main take-away is to use the official [HoloLens UWP app](https://www.microsoft.com/en-us/store/p/microsoft-hololens/9nblggh4qwnx). Note, this (free) app is only available in the American Windows Store (it's easy to switch though).

[https://technology.amis.nl/2016/12/05/demo-microsoft-hololens-and-share-your-screen/](https://technology.amis.nl/2016/12/05/demo-microsoft-hololens-and-share-your-screen/)  
Some demo tips.

[http://www.theverge.com/2017/2/13/14588178/microsoft-hololens-video-capture-augmented-reality-headset-apps](http://www.theverge.com/2017/2/13/14588178/microsoft-hololens-video-capture-augmented-reality-headset-apps)  
If you really want to capture the Hololens experience in a professional way, this is how to do it.

## Official tutorials
[https://developer.microsoft.com/en-us/windows/holographic/academy](https://developer.microsoft.com/en-us/windows/holographic/academy)  
This should be your first tutorial to start with. You get a good sense of all possibilities with HoloLens. Furthermore you can check your dev setup (_is everything installed correctly? Does the simulator work?_). A disadvantage of these tutorials is that you only get to copy and paste code, without much explanation what exactly you are doing. Therefore some third-party bloggers have created some references where they try to explain their findings.

## Third Party References
There are three main bloggers for the moment: Morten Nielsen ([@dotMorten](https://twitter.com/dotMorten)) was one of the first .NET developers getting his hands on a real device. He created some guidelines on how to set-up Unity correctly for creating HoloLens experiences. Next, Joost van Schaik ([@LocalJoost](https://twitter.com/localjoost)) created some non-trivial demos and documented everything with source code available on Github. Then there's Mike Taulty ([@mtaulty](https://twitter.com/mtaulty)), who takes a deep dive into the HoloToolkit. At the moment, this is the most important (only?) C# library with some useful components. Finally there's Rick Barrazza ([@rickbarrazza](https://twitter.com/rickbarraza)) who has a video series on Creative Coding and where you can grasp some nice Unity concepts and how to program in Unity with C#.

### Morten Nielsen
Morten blogs mostly on IoT and GIS, but started recently to blog about HoloLens. He did some nice write-ups on some really basic stuff, where he actually explains what happens and why you should set certain properties.

[http://sharpgis.net/post/2016/04/10/Creating-your-very-first-holographic-app-in-Unity](http://sharpgis.net/post/2016/04/10/Creating-your-very-first-holographic-app-in-Unity)  
How to do _File &gt; New Project_ in Unity and make it HoloLens aware. Update: this is still good info, but probably a little dated. If you install the HoloToolkit, it creates an extra menu in Unity where you can automate this stuff.

[http://sharpgis.net/post/2016/04/10/Using-HoloLens-Spatial-Mapping-to-occlude-objects](http://sharpgis.net/post/2016/04/10/Using-HoloLens-Spatial-Mapping-to-occlude-objects)  
[http://sharpgis.net/post/2016/04/14/Rendering-the-Spatial-Mapping-Mesh](http://sharpgis.net/post/2016/04/14/Rendering-the-Spatial-Mapping-Mesh)  
[http://sharpgis.net/post/2016/04/14/Adding-a-Gaze-Cursor-to-your-HoloLens-App](http://sharpgis.net/post/2016/04/14/Adding-a-Gaze-Cursor-to-your-HoloLens-App)

### Joost van Schaik
The _Cube Bouncer_ is an app that creates some cubes and explores several possibilities for manipulating them. Source code is out in the open and explained in full detail.

[http://dotnetbyexample.blogspot.be/2016/07/hololens-cubebouncer-application-part-1.html](http://dotnetbyexample.blogspot.be/2016/07/hololens-cubebouncer-application-part-1.html)
[http://dotnetbyexample.blogspot.com/2016/07/hololens-cubebouncer-application-part-2.html](http://dotnetbyexample.blogspot.com/2016/07/hololens-cubebouncer-application-part-2.html)
[http://dotnetbyexample.blogspot.com/2016/07/hololens-cubebouncer-application-part-3.html](http://dotnetbyexample.blogspot.com/2016/07/hololens-cubebouncer-application-part-3.html)
[http://dotnetbyexample.blogspot.com/2016/07/hololens-cubebouncer-application-part-4.html](http://dotnetbyexample.blogspot.com/2016/07/hololens-cubebouncer-application-part-4.html)
[http://dotnetbyexample.blogspot.nl/2016/07/hololens-cubebouncer-application-part-5.html](http://dotnetbyexample.blogspot.nl/2016/07/hololens-cubebouncer-application-part-5.html)

A second app is a _real_ case: a visualisation of air traffic data of Amsterdam airport. You can actually [download](https://www.microsoft.com/en-us/store/p/ams-holoatc/9nblggh52szp) and run this app (is uses only historic data).

[http://dotnetbyexample.blogspot.be/2016/10/a-hololens-airplane-tracker-1.html](http://dotnetbyexample.blogspot.be/2016/10/a-hololens-airplane-tracker-1.html) 
[http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-2setting-up.html](http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-2setting-up.html)
[http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-3creating.html](http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-3creating.html)
[http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-4reading.html](http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-4reading.html)
[http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-5-smooth.html](http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-5-smooth.html)
[http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-6adding.html](http://dotnetbyexample.blogspot.com/2016/10/a-hololens-airplane-tracker-6adding.html)
[http://dotnetbyexample.blogspot.com/2016/11/a-hololens-airplane-tracker-7activating.html](http://dotnetbyexample.blogspot.com/2016/11/a-hololens-airplane-tracker-7activating.html)
[http://dotnetbyexample.blogspot.com/2016/11/a-hololens-airplane-tracker-8adding.html](http://dotnetbyexample.blogspot.com/2016/11/a-hololens-airplane-tracker-8adding.html)

From the same author and also worth a read:

[http://dotnetbyexample.blogspot.be/2017/01/scanning-physical-objects-with-xbox-one.html](http://dotnetbyexample.blogspot.be/2017/01/scanning-physical-objects-with-xbox-one.html)  
Scan an object with Kinect and use it within a HoloLens app.

[http://dotnetbyexample.blogspot.be/2017/02/using-hololens-scanned-room-inside-your.html](http://dotnetbyexample.blogspot.be/2017/02/using-hololens-scanned-room-inside-your.html)  
Visualize the meshed grid HoloLens creates from your rooms and how to enhance it.

[http://dotnetbyexample.blogspot.be/2017/02/a-generic-toggle-component-for-hololens.html](http://dotnetbyexample.blogspot.be/2017/02/a-generic-toggle-component-for-hololens.html)  
A generic toggle component that you can attach to your own prefabs.

## Mike Taulty
Mike is a Microsoft employee focusing mostly on UWP and IoT, but recently he started to disect the [HoloToolkit](https://github.com/Microsoft/HoloToolkit-Unity ). Although his first posts on the subject are already dated (since the HoloToolkit source code has changed), his approach to reading and experimenting with the source code is very instructive.

[https://mtaulty.com/2016/11/10/hitchiking-the-holotoolkit-unity-leg-1/)](https://mtaulty.com/2016/11/10/hitchiking-the-holotoolkit-unity-leg-1/)  
Installation proces for HoloToolkit into your own projects. Note that once you install this toolkit, a number of required steps to tweak Unity for development are scripted into a seperate HoloToolkit menu.

[https://mtaulty.com/2016/11/11/hitchiking-the-holotoolkit-unity-leg-2/](https://mtaulty.com/2016/11/11/hitchiking-the-holotoolkit-unity-leg-2/)  
This is not accurate anymore, but his way of approaching the HoloToolkit source code is very instructive. Worth your time.

### Rick Barazza
Rick is a so called [Creative Coder](https://en.wikipedia.org/wiki/Creative_coding). If you never used Unity before, he explains it in a very developer friendly way.

[https://channel9.msdn.com/Series/UnityCreativeCoding](https://channel9.msdn.com/Series/UnityCreativeCoding)  

### Some other references
[https://forums.hololens.com/discussion/5967/hololens-tutorial-simple-projectile-using-the-latest-holotoolkit](https://forums.hololens.com/discussion/5967/hololens-tutorial-simple-projectile-using-the-latest-holotoolkit)  
This tutorial explains how to create a projectile.

[http://www.pluralsight.com/courses/hololens-development-fundamentals](http://www.pluralsight.com/courses/hololens-development-fundamentals)  
A Pluralsight course that creates a simple game.

[http://peted.azurewebsites.net/hololens-3d-mapping/](http://peted.azurewebsites.net/hololens-3d-mapping/)  
Convert 3D mapping data to a Unity Mesh.

[https://blogs.windows.com/buildingapps/2017/03/06/building-terminator-vision-hud-hololens/#ZDXloUkFVUliSfBx.97](https://blogs.windows.com/buildingapps/2017/03/06/building-terminator-vision-hud-hololens/#ZDXloUkFVUliSfBx.97)  
The famous Terminator HUD as a HoloLens app, _with source code_!

## Libraries

For the moment, there's the HoloToolkit:

[https://github.com/Microsoft/HoloToolkit](https://github.com/Microsoft/HoloToolkit)  
[https://github.com/Microsoft/HoloToolkit-Unity](https://github.com/Microsoft/HoloToolkit-Unity)  

## Cool demos
[http://uploadvr.com/building-with-hololens/](http://uploadvr.com/building-with-hololens/)  
Use HoloLens in a building project

[https://www.youtube.com/watch?v=0rE4MwLK1eE&feature=youtu.be](https://www.youtube.com/watch?v=0rE4MwLK1eE&feature=youtu.be)  
Map of a campus

[https://mspoweruser.com/taqtile-brings-3d-maps-hololens-video/](https://mspoweruser.com/taqtile-brings-3d-maps-hololens-video/)  
Real-time and 3D rendering of Bing Maps with actual weather and traffic information

[https://blogs.windows.com/buildingapps/2017/03/06/building-terminator-vision-hud-hololens/#ZDXloUkFVUliSfBx.97](https://blogs.windows.com/buildingapps/2017/03/06/building-terminator-vision-hud-hololens/#ZDXloUkFVUliSfBx.97)  
The famous Terminator HUD as a HoloLens app, _with source code_!

[http://blog.htmlfusion.com/controlling-lights-with-the-hololens-and-internet-of-thingsatch-one-of-philippes-appearances-in-june/](http://blog.htmlfusion.com/controlling-lights-with-the-hololens-and-internet-of-thingsatch-one-of-philippes-appearances-in-june/)  
Control Philips Hue lights
[https://medium.com/microsoft-design/designing-typography-insight-for-hololens-a55fc5fe025#.xi6zrai5j](https://medium.com/microsoft-design/designing-typography-insight-for-hololens-a55fc5fe025#.xi6zrai5j)
Designing typography insight

