
MovieHunter: Angular-WebAPI
================================

Sample beginner Angular application using NancyFx for the Web API. 

This is a complete rewrite of the [original fork!](https://github.com/DeborahK/Angular-MovieHunter-WebAPI) Using **Nancy.Hosting.Aspnet** that I did for study purpose.  
I created an fork of this repo using MongoDB https://github.com/RafaelDelboni/Angular-WebAPI-MongoDB


### Server Requirements

**NancyFX** was designed to not have any dependencies on existing frameworks. Built with the .NET framework client profile, Nancy can be used pretty much wherever you want to, since it’s completely self contained with its own request and response objects.
https://github.com/NancyFx/Nancy/wiki/Documentation#hosting

### For Xamarin Studio users

Since Xamarin don't support just websites projects and just one debug XSP running per instance, I've splitted the projects (API and UI), so you will need two separated Xamarin Studio's instances running. 

If you use Xamarin Studio on Mac and want an easy way to run multiple instances, don't forget to check this out:
http://redth.codes/Xamarin-Studio-Launcher-v3/