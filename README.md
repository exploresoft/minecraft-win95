# minecraft-win95
A patch that makes Minecraft Classic 0.0.12a-dev playable with Windows 95. 

I'm not going to upload the patched 0.0.12a-dev JAR file because of legal reasons.

## How to apply the patch?
Replace com.mojang.minecraft.Minecraft with the patched Minecraft.class

Replace com.mojang.minecraft.renderer.Textures with the patched Textures.class

## How to run after patching?
Type "java -cp client.jar;lwjgl.jar -Djava.library.path=natives com.mojang.minecraft.Minecraft" in the MS-DOS Prompt and press enter, or just paste it to a batch file and run that batch file.

Make sure that LWJGL's .jar files and the native folder is in the same directory you're in, otherwise this command won't work.

## Software Requirements for Windows 95
- Java SE 5
- LWJGL 0.98 or 0.99 
- OpenGL 1.1

## Notes
- 0.0.12a-dev is the same one as c0.0.11a in the Minecraft Launcher.
- **0.99** is the latest version of LWJGL that works in Windows 95 AND launches Minecraft, newer versions will give a DLL initialization error or a device not functioning error.
- Running 0.0.12a-dev without patches will open the window, but it will give a missing GLU error, because GLU is added in LWJGL 2.0 beta 1.
- **THIS IS ONLY FOR EDUCATIONAL PURPOSES ONLY. I DO NOT OWN MINECRAFT, ALL RIGHTS ARE OWNED BY MOJANG STUDIOS**

## Screenshots

<img width="640" height="480" alt="Monitor_1_20250907-173827-134" src="https://github.com/user-attachments/assets/4d1d3e4a-eebc-4bbd-801a-210f3eb5c6bd" />

<img width="640" height="480" alt="Monitor_1_20250907-182851-375" src="https://github.com/user-attachments/assets/cc2ff793-f8d9-419f-a6eb-00067d09f269" />
