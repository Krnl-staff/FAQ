# Failed to access DLL file
It is unknown why this occurs, although we have some steps which have fixed this issue for others.

![image](https://user-images.githubusercontent.com/57600814/199680683-e1922c90-68d9-4b48-84ef-6ea96467228e.png)

## Solutions
* Launch Krnl as administrator.
* If you are using the latest Krnl UI; Press `Win + R`, type `%appdata%/Krnl`, delete "krnl.dll" and "injector.dll" and relaunch the UI.

* If none of the above works, then your Windows user might have non-latin characters that prevents Krnl from accessing the dll. A fix to this is pressing the Windows key + R and typing `C:\Users\Public`, then drag the Krnl folder into the `Public` folder. Try to use Krnl and it should now work.
