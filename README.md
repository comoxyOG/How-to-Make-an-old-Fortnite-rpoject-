# How-to-Make-an-old-Fortnite-rpoject-
How to make an old Fortnite project!

<details>
  <summary>The CHATGPT Python Way</summary>
  What to send: 
"Make me an ALL-IN-ONE offer! (LAUNCHER FOR FORTNITE!)

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
"
</details>
