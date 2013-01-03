# Problems

During the development of the game a lot unique problems appeared:

### Debugging

Debugging normal web apps has become really easy in the last years with all browser vendors shipping their own debug tools with their browsers. For example in Google Chrome there are the '[Chrome Developer Tools](https://developers.google.com/chrome-developer-tools/docs/overview)' which provide developers with a console, a debugger, memory management tools, network logs and much more.

Even debugging web apps on mobile devices has been enabled by Google very recently. By activating a specfic configuration in their Android operating system the mobile phone will forward all debug information to a TCP port of the connected computer. The Chrome Developer Tools can connect to this port and provide the same tools to debug web apps on mobile phones as can be used to debug websites on normal computers. [1](https://developers.google.com/chrome/mobile/docs/debugging)

One major advantage of this system is that it enables cross-platform (limited to the operating systems that Google Chrome runs on, of course) debugging with the same tool chain. Also the documentation of these tools is very detailed and a lot of videos show how to use the tools.

Concluding that, it can be said that debugging web apps normaly is an easy task and there are powerful tools which help developers.

Unfortunately, nothing like that can be said about the debugging capabilities of the Samsung SmartTV platform. The provided tools are very limited and the typical development flow for developing web apps is broken.

Normally, several `console.log(x)`-statements would be inserted in the code, in order to test a feature or find a bug. This would lead to some output in the browser's development console (which even the IE8 has). When running this command on the device, the app would simply crash without showing a reason or even not start at all. The emulator, on the other side, is capable of showing the log-statements which is totally inconsistent. In order to run the app on the device, all console-statments have to be removed or it will not work, allthough the emulator says so.



### No cross-platform

First of all, the SDK is only provided for Microsoft Windows which makes it impossible to run the emulator or install the editor on other operating systems. 


### Poor emulator

When running an app in the emulator 
- app runs on emulator -> does not run on TV

### Poor documentation

### Platforms outdate extremely fast