# Minecraft Launcher Instructions

The official [Minecraft Launcher](https://www.minecraft.net/en-us/download#alternate-versions) is known for [sucking](https://www.reddit.com/r/Minecraft/comments/1cgt9ns/why_does_the_pc_launcher_suck) but if you want to use it **anyways**, today's your lucky day, just follow the steps.

## 1. Download the Installer

### Installer for Official Minecraft Launcher
> [!CAUTION]
> The Installer may cause issues and (possibly) break your game, or else. Depending on operating system.

[![Download Experimental Installer](https://img.shields.io/badge/Download-Experimental_Installer-critical?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/k4sprl/massively-optimized/main/official-launcher/MassivelyOptimizedInstaller.jar) `.jar`

<img width="16" height="16" src="https://cdn.simpleicons.org/linux/FFFFFF"> <img width="16" height="16" src="https://cdn.simpleicons.org/apple/FFFFFF"> <img width="16" height="16" src="https://github.com/user-attachments/assets/072b93f6-f380-47f1-8871-11a5eae92317" />

## 2. Run the Installer

Before you can run the downloaded `.jar` file, you need to ensure you have a valid version of Java installed on your system (Java 17 or 21 is recommended for modern Minecraft versions; refer to your chosen profile's requirements). If you don't have it, grab it from [Adoptium](https://adoptium.net).

> [!NOTE]
> On Windows and Mac, you can usually just double-click the `.jar` file. If it opens in an archive manager (like WinRAR or 7-Zip) by mistake, right-click the file -> **Open with** -> **Java(TM) Platform SE binary**.

Alternatively, you can run it directly via your terminal or command prompt:
```bash
java -jar MassivelyOptimizedInstaller.jar

```

## 3. Install the Profile

Once the 'Massively Optimized Installer for MC Launcher' GUI pops up, follow these steps to generate your new installation profile:

1. **Select Minecraft Version:** Choose your desired Minecraft game version from the dropdown menu (e.g., `1.21.11`). The installer allows you to pick a specific version, ensuring you get exactly what you need.
2. **Verify Profile Name:** A unique profile name will automatically generate (e.g., `Massively Optimized 1.21.11`). You can change this text field to customize the profile's name in the launcher.
3. **Confirm Install Directory:** The installer will attempt to automatically detect your default Minecraft directory. For reference, those are usually:
* **Windows:** `%appdata%\.minecraft`
* **Mac:** `~/Library/Application Support/minecraft`
* **Linux:** `~/.minecraft`
If the path is incorrect, click the `Browse...` button to select the correct location.


4. **Click Create Profile:** Once all settings are correct, click the big blue **CREATE PROFILE** button. The installer will download the necessary modpack files and weave them into the launcher's directory.

> [!TIP]
> Wait for the process to complete and a success message to appear. You can safely close the installer after this.

## 4. Open the Launcher & Play

Now for the moment of truth. Open the official Minecraft Launcher that you insisted on using.

1. Navigate to the **Minecraft: Java Edition** tab on the left sidebar.
2. Click the installation drop-down menu situated to the left of the big green **PLAY** button.
3. Look for the profile you just created (e.g., **Massively Optimized 1.21.11**).
4. Select it, acknowledge the launcher's obligatory warning about modified installations, and hit **PLAY**.
