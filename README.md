## HTML Mobile App

This app was created using [`@capacitor/create-app`](https://github.com/ionic-team/create-capacitor-app),
It's not just a raw html project because it's impossible "yet" but it does the work

Using vite to run the server and capacitor contain the code so that it works on mobile phones

### Running this example

To run the provided example, you can use `npm run dev` command.

Or build it using `npm run build` and run it using `npm run start`

### How to compile it for android?

if you finished editing your code use `npm run build` to build it.
`npx cap sync` to push changes to android folder.
then `npx cap open android` to open it on android studio and run it on you android device

### How to compile it for ios?

First of all you should run this code on a "mac" that has xcode installed.

if you finished editing your code use `npm run build` to build it.
`npx cap add ios` to create ios folder.
`npx cap sync` to push changes to ios folder.
then `npx cap open ios` to open it on xcode and run it on you ios device.
