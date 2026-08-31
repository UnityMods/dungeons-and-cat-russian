# dungeons-and-cat-russian
 
   Unofficial Russian localization for **Dungeons And Cat**. Powered by BepInEx with Windows and Linux/Proton support.
 
   ## Installation
 
   1. Install [BepInEx 5 (x64)](https://github.com/BepInEx/BepInEx/releases) into the game directory.
   2. Download and extract the latest release.
   3. Copy the `DacRussian` folder into:
 
      ```text
      .../SteamLibrary/steamapps/common/Dungeons And Cat/BepInEx/plugins/ ```
   4. The resulting structure should look like this:
    ```
     Dungeons And Cat/
     └── BepInEx/
         └── plugins/
             └── DacRussian/
                 ├── DacRussian.dll
                 └── translations.json
    ```
   5. Start the game and select **English** in the language settings.
 
   ## Linux / Proton
 
   Add the following Steam launch option:
 
   ```bash
   WINEDLLOVERRIDES="winhttp=n,b" %command%
