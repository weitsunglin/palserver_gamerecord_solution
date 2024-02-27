# palserver-GUI-0.0.9-BETA

game recodrs: 
0.0.9-palserver-GUI-win32-x64\resources\app\saves
0.0.9-palserver-GUI-win32-x64\resources\app\engine\steamapps\common\PalServer\Pal\Saved


error message:The match you are trying to join is running an incompatible version of the game. Please try upgrading your game version.
solution: 
1. steamcmd download
2. terminal cd into steamcmd path
3. steamcmd +login anonymous +app_update 2394010 validate +quit
4. steamapps 刪除2394010，資料丟到0.0.9-palserver-GUI-win32-x64\resources\app\engine\steamapps
