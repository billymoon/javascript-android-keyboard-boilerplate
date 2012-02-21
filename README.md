## Overview

This project is in it's early stages, and hopes to generate some interest from other developers who might take it further.

I am aiming to make a boilerplate software keyboard for Android devices which uses a web-view to allow the main interactive area to be written in javascript and HTML. This should allow front-end developers the chance to create interesting alternative interfaces for android keyboards without learning a lot of Java and Android development.

## Plans

I plan to add more hooks to the native interface to be accessed via javascript function calls.

## How to use

If you have android-sdk-9 installed, you should be able to build this using `ant build` from within the project's `SoftKeyboard` directory (at least it works for me with my setup). Other building instructions welcome, please let me know how to do it using Eclipse for example...

Once built, install the `bin/SoftKeyboard-debug.apk` file to your android device or emulator.