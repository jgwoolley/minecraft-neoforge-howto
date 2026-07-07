# How to Install Forge / NeoForge

## Terminology

* **Mod Loader:** A piece of software that "hooks" into the game code, allowing it to load custom modifications (mods) that change gameplay, add items, or improve performance.
* **Installer (.jar):** A file format used by Java applications. You "run" this file to automate the process of patching your game files.
* **Instance / Game Directory:** A separate folder where all your specific game data for a certain mod setup lives. Using unique folders prevents different mod packs from conflicting with each other.
* **JRE (Java Runtime Environment):** The software that allows your computer to read and execute Java-based programs like the Minecraft mod installers.
* **Profile:** A configuration setting in the Minecraft Launcher that tells the game which version and folder path to use when you click "Play."
* **.minecraft Folder:** The default data directory for Minecraft. 
    * **Windows:** `%AppData%\.minecraft`
    * **macOS:** `~/Library/Application Support/minecraft`
    * **Linux:** `~/.minecraft`

## What you will need

*   **Microsoft Account:** Required to access Minecraft Java Edition.
*   **Minecraft Java Edition:** Installed and launched at least once.
*   **Java JRE:** Required to run the Mod Loader installers (check the version requirement for your specific MC version).
*   **Mod Jar Files:** The mods you intend to use.
*   **Optional:** Server IP Address / Whitelist (if connecting to a specific server).

## Steps

1. **Install Minecraft:** Ensure you have the version of the game you intend to mod installed. Close the launcher completely.
1. **Install Java:** Ensure you have the correct version of Java installed (e.g., Java 21 for 1.21+).
1. **Download the NeoForge Installer:** Download the official `.jar` file from the [NeoForged website](https://neoforged.net/).
1. **Ensure Executability:** If the file does not open, ensure it is set to open with your Java executable.
1. **Run the Installer:** Right-click the `.jar` file and select "Open with" > "Java".
1. **Install Client:** Select "Install Client" and click "Proceed". Ensure the path points to your `.minecraft` folder (see location guide in the Terminology section).
1. Create a installations folder inside of your `.minecraft` folder:
    * **Windows:** `%AppData%\.minecraft\installations`
    * **macOS:** `~/Library/Application Support/minecraft/installations`
    * **Linux:** `~/.minecraft\installations`
1. **Launch the Launcher:** Open the Minecraft Launcher.
1. **Create Custom Installation:**
    *   Navigate to the **Installations** tab.
    *   Click **New Installation**.
    *   **Name:** Give it a descriptive name (e.g., `NeoForge 1.21.1`).
    *   **Version:** Select the version in the dropdown that includes `neoforge` in the title.
    *   **Game Directory:** Click **Browse** and create a unique folder inside your `.minecraft` directory (e.g., `.minecraft/instances/NeoForge_1_21_1`).
    *   Click **Create**. (Note: You can ignore or delete the default "NeoForge" profile created by the installer if you prefer using this custom one).
1. **Initialize Directory:** Select your new profile from the play menu and click **Play**. Let the game load to the main menu so it can generate the required configuration files and folders, then quit the game.
1. **Install Mods:**
    *   Open the folder you created in step 8.
    *   Locate (or create) the `mods` folder inside it.
    *   Drag and drop your desired `.jar` mod files into this folder.
1. **Play:** Select your custom profile in the launcher and click **Play** to start the game with your mods.