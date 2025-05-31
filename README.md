# How-to-Make-an-old-Fortnite-Project-
**How to make an old Fortnite project!**

<details>
  <summary>The CHATGPT Python CLI WAY (CMD)</summary>
  What to send to chatgpt: 
"**Make me an ALL-IN-ONE offer! (LAUNCHER FOR FORTNITE!)

I want you to make an Old Fortnite Launcher that:

- Asks for a Username, and a folder containing both "FortniteGame" and "Engine".
- Navigates to: FortniteGame > Binaries > Win64 > FortniteClient-Win64-Shipping.exe
- Launches the game with the following arguments:
    - -EpicPortal
    - -nobe
    - -log
    - -AUTH_TYPE=epic
    - -epicapp=Fortnite
    - -caldrea= (a 24-digit hex string)
    - -AUTH_LOGIN={username}@Comoxy.dev
    - -AUTH_PASSWORD=FILLER  # This is hardcoded

Then:

- Locate the following DLLs in the same directory as the Python script:
    - Paradise.dll
    - Project Reboot 3.0.dll
- Inject both DLLs into the Fortnite process immediately after it starts, using LoadLibraryW.
- The launcher must stay open and **cannot close** after launch or injection.

CODING LANGUAGE: Python
**
GUI OR NO GUI: ANSWER NO GUI; Make it a CLI
PS: MAKE IT INJECT THE DLLS AS SOON AS FORTNITE LAUNCHES
"
</details>

<details>
  <summary>The CHATGPT HTML Way</summary>
  What to send to chatgpt: 
"**Make me an ALL-IN-ONE offer! (LAUNCHER FOR FORTNITE!)

I want you to make an Old Fortnite Launcher that:

- Asks for a Username, and a folder containing both "FortniteGame" and "Engine".
- Navigates to: FortniteGame > Binaries > Win64 > FortniteClient-Win64-Shipping.exe
- Launches the game with the following arguments:
    - -EpicPortal
    - -nobe
    - -log
    - -AUTH_TYPE=epic
    - -epicapp=Fortnite
    - -caldrea= (a 24-digit hex string)
    - -AUTH_LOGIN={username}@Comoxy.dev
    - -AUTH_PASSWORD=FILLER  # This is hardcoded

Then:

- Locate the following DLLs in the same directory as the Python script:
    - Paradise.dll
    - Project Reboot 3.0.dll
- Inject both DLLs into the Fortnite process as soon as it starts using A DLL injector for HTML.
- Set up an HTTP redirect server to listen on: http://127.0.0.1:3551

CODING LANGUAGE: HTML**
</details>

<details>
  <summary>The CHATGPT Python Way, GUI</summary>
Send this to chatgpt:
  Make me an ALL-IN-ONE offer! (LAUNCHER FOR FORTNITE!)

I want you to make an Old Fortnite Launcher that:

- Asks for a Username, and a folder containing both "FortniteGame" and "Engine".
- Navigates to: FortniteGame > Binaries > Win64 > FortniteClient-Win64-Shipping.exe
- Launches the game with the following arguments:
    - -EpicPortal
    - -nobe
    - -log
    - -AUTH_TYPE=epic
    - -epicapp=Fortnite
    - -caldrea= (a 24-digit hex string)
    - -AUTH_LOGIN={username}@Comoxy.dev
    - -AUTH_PASSWORD=FILLER  # This is hardcoded

Then:

- Locate the following DLLs in the same directory as the Python script:
    - Paradise.dll
    - Project Reboot 3.0.dll
- Inject both DLLs into the Fortnite process as soon as it starts using LoadLibraryW.
- Set up an HTTP redirect server to listen on: http://127.0.0.1:3551

CODING LANGUAGE: Python
GUI OR NOT GUI; .MAKE IT GUI, OR WITH A UI; NO CLI, JUST GUI OR UI!
</details>


