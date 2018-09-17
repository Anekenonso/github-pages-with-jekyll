---
title: "How to stop excess data consumption in windows 10"
date: 2018-09-17
---

If you have been using windows 10 for a while now or you are totally new to Windows 10, one thing you should have noticed is that the data consumption is much compared to using previous windows operating system.

Microsoft current OS windows 10 are built in such a way that when you are connected to the internet, other windows 10 users can download updates through your computer.  This was built so as to reduce the stress in downloading updates. Instead of downloading the updates from Microsoft server users can download the updates through other users computer you have already downloaded the update.  in return, it helps to reduce the number of requests that go to the server.

Windows 10 by default checks for update and downloads update automatically without prompting the user about it, but this can be changed to check to updates automatically but lets the user decide if he/she wants to download it immediately or to download it when the user has enough data for updates.

How to stop excess data consumption
There are so many ways in which to stop excess data consumption in Windows 10. We shall look at one of the ways in which to stop excess data consumption.
    Turn off updates
I do not advise that you take this method unless you know what you are doing, turning off updates will cause your computer to stop receiving windows update and security updates which in return exposes your computer to a virus.

1.       Press Windows button +R  on your keyboard to start a run command
2.       Type services.msc  and hit enter
3.       Scroll down till you see **windows update**. Right-click and select **properties**.
4.       Under **startup type** select  **disable**
5.       Click okay. And that’s it, windows update service have been disabled and will no longer start up with your computer.

But there is a better option. As mentioned before this is not a very good idea. The best option is to launch Group Policy Editor and select the option Notify for download and notify for install. This lets you choose when to download and install updates.
With this, the excess data consumption should stop.

