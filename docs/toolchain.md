---
layout: page
---

# Installing Software On Your Home Computer

## Unity

Unity can be installed on any reasonably modern computer running Linux, macOS, or Windows. I've heard reports of people succussfully installing Unity on a ChromeBook (which is running Linux "under the covers"), but I don't have a ChromeBook to test on. The restrictions on SKSD ChromeBooks will probably make installing Unity impossible for now (as of 9 Apr 2020).

Do not install Unity directly, instead install Unity Hub and use it to manage your Unity installs.

### Instructions:

* [Linux (not ChromeBook), macOS, and Windows](https://unity3d.com/get-unity/download) – download and install Unity Hub **not** Unity itself. Once you have Unity Hub installed, use it to install Unity. Install version **2018.4 (LTS)** for Create with Code. Supported OS versions:
  - Linux: Umbutu 16.4, 18.4, or CentOS 7
  - macOS: 10.12 (Sierra) or later
  - Windows: 7 (SP1), 8, or 10 – 64-bit only
* A personal (not SKSD) **ChromeBook** – I don't have a ChromeBook to experiment with (yet), but I've found a number of posts on the Internet that claim to show you how to install Unity on a ChromeBook by enabling Linux programs. Here are some links that you might find helpful if you want to give this a try:
  - [Unity3D is running natively on my Chromebook and I couldn’t be happier!](https://medium.com/@alexanderhaskins/unity3d-is-running-natively-on-my-chromebook-and-i-couldnt-be-happier-512a0c4b5e32) – this post is an overview of enabling Linux apps on a ChromeBook and then installing Unity. The post was written in 2018, so use it more as a guide to what the process is and keep in mind that the process may have evolved and gotten easier.
  - [Complete Guide to Installing Linux on Chromebook](https://itsfoss.com/install-linux-chromebook/) – this post is from 2019 and explains how to replace ChromeOS with Umbutu Linux, you may want to think hard about making that move. A more conservative approach would be to run Linux apps alongside ChromeOS.
* SKSD **ChromeBook** – at this point (9 April 2020) I don't know of a way to install Unity on an SKSD ChromeBook. I'm hoping to learn more about the options and this may change.

## Source Code Editor

Once you get Unity installed, you'll need a program to edit your C# scripts. Unity comes with Microsoft's Visual Studio. In our lab at SKHS we using Visual Studio Code since it doesn't require you to create a Microsoft account. There are versions of Visual Studio Code for Linux, macOS, and Windows.

### Installing
* **Visual Studio** – A 30-day trial of Visual Studio is installed by default when you install Unity. After 30 days you can keep using it by creating a Microsoft account.
* [Visual Studio Code](https://code.visualstudio.com) – in our lab at SKHS we were using VS Code, mainly because it does not require you to create a Microsoft account. It will recognize your operating system and offer a download of the stable version by default. After installing VS Code, you'll need to configure Unity to use it in the Unity preferences.
