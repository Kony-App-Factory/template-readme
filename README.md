# Repository Name

Name your repo something readable and easily recognisable. Not necessarily the name of the repo in the url, but perhaps the commercial name of the app or project -e.g. If it's an image analysis app and the repo is named imgAnalRastFooBar, just add a heading that reads "Image Analysis App" and then use this space to describe what it's about. Try to answer briefly questions like whether it's an actual App to be delivered or just a Proof of Concept (PoC), what it does, who it's for.

## Type of Repo

Make sure you only mark one. If you're tempted to mark more than one, then it's probably because you're mixing two projects in the same repo. Consider **breaking it into several repos**. For example, if you have an app that uses Android FFI, you'll want to put your Android code in a separate repo. Then document the "Dependencies" section below to say your app has a dependency on that repo.

- Kony App
  - [x] B2C
  - [ ] B2E
- Mobile Fabric Export
  - [ ] Identity Service
  - [ ] Integration Service
  - [ ] Orchestration Service
  - [ ] Object Service
- Reusable Javascript
  - [ ] Javascript Component or Library
- Foreign Function Interface (FFI)
  - [ ] Javascript Interface to an FFI
  - [ ] Android
  - [ ] iOS
  - [ ] Windows
- Other
  - [ ] Custom Java Service

## Channels Targeted

Select all the platforms targeted for this project.

- Mobile
  - [x] iOS
  - [x] Android
  - [ ] Windows Phone 8.x
- Tablet
  - [ ] iOS
  - [ ] Android
  - [ ] Windows 8.x
- Desktop
  - [ ] Desktop Web
  - [ ] Desktop Windows
- Smart Watch
  - [ ] Apple Watch

## Dependencies

Describe and link here all the other projects or repositories on which your project depends. These could be Mobile Fabric services, FFI or reusable Javascript components. For example, if your project uses [Lodash](https://lodash.com/), [Q](https://github.com/mig82/q) or [Jasmine](http://jasmine.github.io/2.4/introduction.html), say so, describe why and how, and add the relevant links here.

## How to Build

If your repo is an FFI add, a detailed list of the commands or instructions to build it.

    javac MyJavaFFI

## How to Install

If you repo is a reusable Javascript library or an FFI, add the instructions to import it into a Kony App.
If your repo is a Mobile Fabric service, add the instructions on how to import it to Mobile Fabric.

    bower install MyReusableModule

## How to Use

If your repo is a reusable Javascript library or an FFI, add snippets of code on how to use it in a Kony App.

    var test = new MyReusableModule();
    var foo = test.bar();

## Implementation Notes

Use this space to make comments on relevant details of implementation, such as what programming patterns you used, the architecture of the app, the naming conventions to follow, what important workarounds you used, etc. For example:

*"I used the foo library to get around xyz problem. This app uses MVVM or MVP and my presenter objects are named with the prefix/suffix '_Presenter'. All service calls are handled by the ServiceClient module, while all configuration is handled by the ConfigModule module".*

