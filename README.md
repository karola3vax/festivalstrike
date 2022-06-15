1- Downloaded UberStrike.
2- Downloaded and patched game using ParadiseClient and UniversalUnityPatcher.
3- Downloaded ParadiseServer and Photon, used Photon's lib folder for necceseary files;

ExitGames.Logging.Log4Net.dll
ExitGamesLibs.dll
Photon.SocketServer.dll
UnityEngine.dll

Pasted these dll's to ParadiseServer, Paradise.Realtime's bin folder.
Back to our ParadiseServer, Paradise.WebServices, pasted UnityEngine.dll which is found in Uberstrike's root folder.
Back to our ParadiseServer, photon folder, pasted essential files using deploy/binWin64 from PhotonSDK we downloaded earlier.

Installed ParadiseService using InstallParadiseService.bat

4- Headed to UberStrike>\UberStrike_Data\ParadiseSettings.Client.xml and applied github.com/festivaldev/Paradise/wiki/Configuration-Client settings one by one.

5- Created 8080, 8081 port using "inetmgr" command on Windows. Otherwise It would give me connection error when game starts.

6- I gathered needed files for "AssemblyReferences"

7- Downloaded repository, got file named Paradise-master.zip that has Paradise.sln in it. I haven't touched anything.
Now, do I "rebuild" the Paradise.sln without touching anything or do I need to replace these files to for instance to photon root? I have 3 different folders.

(GAME WORKS, I GET 8081 PORT:UPDATE ERROR POP ON THE GAME ON START, PRESSING OK AND SKIPPING IT)
