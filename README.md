# XamarinForms-MobileCenterPush-AppLinks-Repro
A sample Xamarin.Forms app that reproduces System.TypeLoadException when a File -> New Xamarin.Forms app is created and Xamarin.Forms AppLinks + Mobile Center Push Nuget Packages are added to the project


>Could not load type of field 'Xamarin.Forms.Platform.Android.AppLinks.AndroidAppLinks:_client' (0) due to: Could not resolve type with token 01000013 (from typeref, class/assembly Android.Gms.Common.Apis.GoogleApiClient, Xamarin.GooglePlayServices.Basement, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null) assembly:Xamarin.GooglePlayServices.Basement, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null type:Android.Gms.Common.Apis.GoogleApiClient member:<none>

