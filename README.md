# minecraft-win95
A patch that makes Minecraft Classic 0.0.12a-dev (on launcher, c0.0.11a) playable with Windows 95. 

I'm not going to upload the patched 0.0.12a-dev JAR file because of legal reasons.

## How to apply the patch?
Replace com.mojang.minecraft.Minecraft with the patched Minecraft.class

Replace com.mojang.minecraft.renderer.Textures with the patched Textures.class

## How to run after patching?
Type "java -cp client.jar;lwjgl.jar -Djava.library.path=natives com.mojang.minecraft.Minecraft" in the MS-DOS Prompt and press enter.

Make sure that LWJGL is in the same directory, otherwise this command won't work.

## Software Requirements for Windows 95
- Java SE 5
- LWJGL 0.98 or 0.99
- OpenGL 1.1

## Screenshots
<img width="640" height="480" alt="Monitor_1_20250907-173827-134" src="https://github.com/user-attachments/assets/f722dcd3-f1e3-4139-aef8-64b93aa33d59" />

<img width="640" height="480" alt="Monitor_1_20250907-182851-375" src="https://github.com/user-attachments/assets/cc2ff793-f8d9-419f-a6eb-00067d09f269" />
