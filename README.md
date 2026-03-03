# DisQuest [![VirusTotal](https://img.shields.io/badge/DisQuest.exe-0/71-green)](https://www.virustotal.com/gui/file/fcdf4d719b7107691cde489e7375f1d72da9f46822dc33b7307d27ed842abc1e/detection) [![VirusTotal](https://img.shields.io/badge/Dummy.exe-0/72-green)](https://www.virustotal.com/gui/file/90863740539f31a3ba0bb6cbd907ca18e83b01ecb91e50a31e2f27b6a552202e/detection) [![VirusTotal](https://img.shields.io/badge/DisQuest_1.1.0.zip-0/66-green)](https://www.virustotal.com/gui/file/64467a3440375ca7880f62761e0ff9ee186db9c266cbd6541935fd9b90950db5/detection)

A tool that spoofs Discord's game detection and makes quest progress via a dummy process.

## How it works
DisQuest creates a dummy process with the same folder structure, executable name and window title as a real game, this causes Discord to believe that you're playing a real game, allowing you to complete quests without installing any games

- Only active non-video quests are shown (There can be a delay of up to 1 hour before new data is pulled)
- This is likely undetectable unless discord starts looking for DisQuest.exe
- You can change the root folder in the settings menu (I recommend changing this to something like A:/Games depending on your drives)
- Quests for games not in the configs pulled from from [here](https://dotxh.github.io/data.json) will be grayed out with a "Configuration missing" message until a configuration is made for that game



<img width="1250" height="828" alt="549781565-0cb0b8c5-6582-447c-9157-12eac3010e8d" src="https://github.com/user-attachments/assets/c34c4d41-8614-43b5-8fef-fed4a7a2390b" />
