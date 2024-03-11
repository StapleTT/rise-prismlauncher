# How to Install Rise on MultiMC/Prism Launcher
**Note:** This guide only works on Windows and Linux. macOS doesn't work because they have poor OpenGL support. If you have any issues, do not contact Rise support. They do not support third party launchers.

**This guide requires you to have one of the following Minecraft launchers installed:**
- MultiMC
- Prism Launcher
- PolyMC
- Any other fork of MultiMC

## Downloading Java
You will need Java 8 installed for Rise to launch. If you already have Java 8 installed, you can skip this step.

If you are on Windows, download Java from here: https://www.azul.com/core-post-download/?endpoint=zulu&uuid=859ba1f1-aa69-42fb-9fbc-a1225d240e89

If you are on Linux, follow the guide at https://prismlauncher.org/wiki/getting-started/installing-java/

After the installation, your launcher's Java window will look something like this: ![alt text](/images/javapage.png)

## Adding Rise as an instance
Now we will add Rise as an instance in Prism Launcher. This will allow it to be launched just like any other version of Minecraft.

First, add a Vanilla 1.8.9 instance and click "OK" at the bottom right of the window. ![alt text](/images/vanilla-instance.png)
Next, click "Edit" on the right side panel to bring up a window where you configure the instance of Minecraft. ![alt text](/images/editbutton.png)

In the Versions tab, select "Replace Minecraft.jar" on the right side panel. ![alt text](/images/replacejar.png)

This will launch a window where you can locate the Rise jar that you downloaded. It will most likely be titled "RiseCompressed.jar" ![alt text](/images/risejar.png)

## Configuring Java
Even though you have all the files needed to launch Rise from Prism Launcher, you still need to configure the correct Java arguments in order to make it launch properly.

Go to the Settings tab. Here, there will be a box where you can enter the correct Java arguments to launch Rise. 

Enter `-noverify` in the box and click "Close" on the bottom right corner. ![alt text](/images/java-args.png)

## I've done everything right. Now what?
At this point, you should be able to launch Rise without any issues. Since the developers of Rise do not officially support Prism Launcher, send me a message on Discord (@staplett) if you have any issues. ![alt text](/images/rise.png)
