# XamarinForms-MobileCenterPush-AppLinks-Repro
A sample Xamarin.Forms app that reproduces System.TypeLoadException when a File -> New Xamarin.Forms app is created and Xamarin.Forms AppLinks + Mobile Center Push Nuget Packages are added to the project.

# Steps To Reproduce
 1. Download source code from this repro
 2. Open in Visual Studio
 3. Build/Deploy the Xamarin.Android project to an Android Device/Simulator
 4. The Error will occur at Runtime when the app launches

# Error 
>Could not load type of field 'Xamarin.Forms.Platform.Android.AppLinks.AndroidAppLinks:_client' (0) due to: Could not resolve type with token 01000013 (from typeref, class/assembly Android.Gms.Common.Apis.GoogleApiClient, Xamarin.GooglePlayServices.Basement, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null) assembly:Xamarin.GooglePlayServices.Basement, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null type:Android.Gms.Common.Apis.GoogleApiClient member:<none>

# IDE
=== Visual Studio Enterprise 2017 for Mac ===

Version 7.0.1 (build 24)
Installation UUID: 6e5142b4-e8be-4d1c-b75e-4744b0d8c3de
Runtime:
 Mono 5.0.1.1 (2017-02/5077205) (64-bit)
 GTK+ 2.24.23 (Raleigh theme)

 Package version: 500010001

=== NuGet ===

Version: 4.0.0.2323

=== .NET Core ===

Runtime: /usr/local/share/dotnet/dotnet
SDK: /usr/local/share/dotnet/sdk/1.0.1/Sdks
MSBuild SDKs: /Library/Frameworks/Mono.framework/Versions/5.0.1/lib/mono/msbuild/15.0/bin/Sdks

=== Xamarin.Profiler ===

Version: 1.5.4
Location: /Applications/Xamarin Profiler.app/Contents/MacOS/Xamarin Profiler

=== Apple Developer Tools ===

Xcode 8.3.3 (12175.1)
Build 8E3004b

=== Xamarin.Android ===

Version: 7.3.1.2 (Visual Studio Enterprise)
Android SDK: /Users/brandonm/Library/Developer/Xamarin/android-sdk-macosx
	Supported Android versions:
		4.1 (API level 16)
		6.0 (API level 23)
		7.0 (API level 24)
		7.1 (API level 25)

SDK Tools Version: 26.0.2
SDK Platform Tools Version: 25.0.5
SDK Build Tools Version: 26.0.0

Java SDK: /usr
java version "1.8.0_121"
Java(TM) SE Runtime Environment (build 1.8.0_121-b13)
Java HotSpot(TM) 64-Bit Server VM (build 25.121-b13, mixed mode)

Android Designer EPL code available here:
https://github.com/xamarin/AndroidDesigner.EPL

=== Xamarin.iOS ===

Version: 10.10.0.36 (Visual Studio Enterprise)
Hash: d2270eec
Branch: d15-2
Build date: 2017-05-22 16:30:53-0400

=== Xamarin.Mac ===

Version: 3.4.0.36 (Visual Studio Enterprise)

=== Xamarin Inspector ===

Version: 1.2.2
Hash: b71b035
Branch: d15-1
Build date: Fri, 21 Apr 2017 17:57:12 GMT

=== Build Information ===

Release ID: 700010024
Git revision: 7ab1ca2ced6f584e56b7a0d4d321d00775cd95c9
Build date: 2017-05-19 05:44:51-04
Xamarin addins: 08d17158f3365beee5e60f67999e607cce4b3f93
Build lane: monodevelop-lion-d15-2

=== Operating System ===

Mac OS X 10.12.5
Darwin 16.6.0 Darwin Kernel Version 16.6.0
    Fri Apr 14 16:21:16 PDT 2017
    root:xnu-3789.60.24~6/RELEASE_X86_64 x86_64

=== Enabled user installed addins ===

NuGet Package Management Extensions 0.12.2

