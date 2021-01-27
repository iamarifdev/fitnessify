# fitnessify

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## To intgrate with Google Fit
Issue and solution: https://github.com/android/fit-samples/issues/58

I found a solution, it is strange but anyway it works for me:

Delete your Cloud project
Instead of the following instructions from http://developers.google.com/fit/android/get-started create a new project with firebase.
Add an android app in firebase project settings
Add both the SHA1 and SHA256 to it.
Download google-services.json to android/app in your project folder.
Make sure to have my "support email" set on general Project settings.
If this not help, please also check https://stackoverflow.com/questions/54557479/flutter-and-google-sign-in-plugin-platformexceptionsign-in-failed-com-google

Guys have a similar problem with GoogleSignIn

Ref: https://github.com/android/fit-samples/issues/58#issuecomment-765193687