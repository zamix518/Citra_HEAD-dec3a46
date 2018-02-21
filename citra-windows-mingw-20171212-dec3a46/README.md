# Merge log

Scroll down for the original README.md!

|PR Number|Title|Author|Merge Success|
|----|----|----|----|
|[2](https://github.com/citra-emu/citra-canary/pull/2)|Canary Base|j-selby|true|
|[3272](https://github.com/citra-emu/citra/pull/3272)|[WIP] core/arm: Backend-specific context implementations|MerryMage|true|
|[3265](https://github.com/citra-emu/citra/pull/3265)|HLE/APT: Implement GetAppletInfo for LLE applets.|Subv|true|
|[3261](https://github.com/citra-emu/citra/pull/3261)|shader_jit_x64_compiler: Use haddps for horizontal summation|MerryMage|true|
|[3240](https://github.com/citra-emu/citra/pull/3240)|Add button labels for sdl joystick mappings|muemart|true|
|[3192](https://github.com/citra-emu/citra/pull/3192)|ldr_ro: convert to ServiceFramework|wwylele|true|
|[3073](https://github.com/citra-emu/citra/pull/3073)|Citra-qt: Add multiplayer ui|jroweboy|true|
|[3071](https://github.com/citra-emu/citra/pull/3071)|Network: Added an executable to host an dedicated room for local wifi|B3n30|true|
|[3070](https://github.com/citra-emu/citra/pull/3070)|NWM_UDS: add ConnectToNetwork and DisconnectNetwork|B3n30|true|
|[3069](https://github.com/citra-emu/citra/pull/3069)|Announce room webservice|B3n30|true|
|[3026](https://github.com/citra-emu/citra/pull/3026)|Cached sequential access of GetPhysicalPointer|huwpascoe|true|


End of merge log. You can find the original README.md below the break.

------

**BEFORE FILING AN ISSUE, READ THE RELEVANT SECTION IN THE [CONTRIBUTING](https://github.com/citra-emu/citra/blob/master/CONTRIBUTING.md#reporting-issues) FILE!!!**

Citra Emulator
==============
[![Travis CI Build Status](https://travis-ci.org/citra-emu/citra.svg?branch=master)](https://travis-ci.org/citra-emu/citra)
[![AppVeyor CI Build Status](https://ci.appveyor.com/api/projects/status/sdf1o4kh3g1e68m9?svg=true)](https://ci.appveyor.com/project/bunnei/citra)

Citra is an experimental open-source Nintendo 3DS emulator/debugger written in C++. It is written with portability in mind, with builds actively maintained for Windows, Linux and macOS. Citra only emulates a subset of 3DS hardware and therefore is generally only useful for running/debugging homebrew applications.

Citra is even able to boot several commercial games! Some of these do not run at a playable state, but we are working every day to advance the project forward. (Playable here means the same as "OK" on our [game compatibility list](https://citra-emu.org/game).)

Citra is licensed under the GPLv2 (or any later version). Refer to the license.txt file included. Please read the [FAQ](https://citra-emu.org/wiki/faq/) before getting started with the project.

Check out our [website](https://citra-emu.org/)!

For development discussion, please join us at #citra on freenode.

### Development

Most of the development happens on GitHub. It's also where [our central repository](https://github.com/citra-emu/citra) is hosted.

If you want to contribute please take a look at the [Contributor's Guide](CONTRIBUTING.md) and [Developer Information](https://github.com/citra-emu/citra/wiki/Developer-Information). You should as well contact any of the developers in the forum in order to know about the current state of the emulator because the [TODO list](https://docs.google.com/document/d/1SWIop0uBI9IW8VGg97TAtoT_CHNoP42FzYmvG1F4QDA) isn't maintained anymore.

### Building

* __Windows__: [Windows Build](https://github.com/citra-emu/citra/wiki/Building-For-Windows)
* __Linux__: [Linux Build](https://github.com/citra-emu/citra/wiki/Building-For-Linux)
* __macOS__: [macOS Build](https://github.com/citra-emu/citra/wiki/Building-for-macOS)


### Support
We happily accept monetary donations or donated games and hardware. Please see our [donations page](https://citra-emu.org/donate/) for more information on how you can contribute to Citra. Any donations received will go towards things like:
* 3DS consoles for developers to explore the hardware
* 3DS games for testing
* Any equipment required for homebrew
* Infrastructure setup
* Eventually 3D displays to get proper 3D output working

We also more than gladly accept used 3DS consoles, preferably ones with firmware 4.5 or lower! If you would like to give yours away, don't hesitate to join our IRC channel #citra on [Freenode](http://webchat.freenode.net/?channels=citra) and talk to neobrain or bunnei. Mind you, IRC is slow-paced, so it might be a while until people reply. If you're in a hurry you can just leave contact details in the channel or via private message and we'll get back to you.
