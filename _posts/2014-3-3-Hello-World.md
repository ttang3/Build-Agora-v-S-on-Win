Have you ever considered creating a real-time communications application similar to Zoom?

There’s usually a steep learning curve in implementing real-time video communication, which can discourage many developers. Thankfully, the [Agora.io SDK](https://docs.agora.io/en/Agora%20Platform/downloads) is a great and easy solution for this!

In this guide, we’ll walk through all the steps you need to build a social media application on Windows that supports video and Desktop Sharing communication from scratch.

## Prerequisites
1. A basic understanding of Windows C/C++ and UI programming.
2. Agora.io Developer Account.
3. Microsoft VIsual studio 2019 on WIndows 10 and 2 Windows 10 laptops with Camera.

Note: While no Windows Win32  and WIndows UI programming knowledge is needed to follow along, certain basic concepts won’t be explained along the way.

You can find [my demo app](https://github.com/ttang3/Agora_video_call_test/blob/main/video_call/agora_video_call_test.exe) as a reference for this article. Also, you can find [Agora Video SDK API](https://docs.agora.io/en/Video/API%20Reference/cpp/index.html) documents here.

## Overview
1. [Set Up New Project](#SetUpNewProject)
2. Implement Video Device Check Functionality
3. Implement Video Call Functionality
4. Implement Desktop Sharing Functionality

## Set Up New Project <a name="SetUpNewProject"></a>
To start, let’s open Android studio and create a new blank new project.

Open Android Studio and click Start a new Android Studio project.
On the Choose your project panel, choose Phone and Tablet > Empty Activity, and click Next.
Click Finish. Follow the on-screen instructions, if any, to install the plug-ins.
Integrate the SDK
Add the following line in the /app/build.gradle file of your project.
