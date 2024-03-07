# palserver-GUI-0.0.9-BETA 解決方案

遇到小海豹伺服器故障時，請按照以下步驟操作以解決：

## 解決步驟

- 伺服器下載: https://github.com/Dalufishe/palserver-GUI/releases
- 將記錄移到：0.0.9-palserver-GUI-win32-x64\resources\app\engine\steamapps\common\PalServer\Pal\Saved



## 錯誤信息

- **錯誤消息**：The match you are trying to join is running an incompatible version of the game. Please try upgrading your game version.

## 解決步驟

1. **下載 SteamCMD**
   - 訪問 Steam 官網下載 SteamCMD 工具。

2. **打開終端並切換到 SteamCMD 路徑**
   - 解壓 SteamCMD 後，打開終端或命令提示符。
   - 使用 `cd` 命令切換到 SteamCMD 的安裝路徑。
     ```bash
     cd 路徑/to/steamcmd
     ```

3. **使用 SteamCMD 更新遊戲**
   - 在 SteamCMD 目錄下執行以下命令，以匿名登錄並更新遊戲：
     ```bash
     steamcmd +login anonymous +app_update 2394010 validate +quit
     ```

4. **替換遊戲文件**
   - 導航至 `SteamCMD 底下 steamapps` 目錄，刪除 `2394010` 文件夾。
   - 將更新後的遊戲文件複製到 `0.0.9-palserver-GUI-win32-x64\resources\app\engine\steamapps` 目錄下。

簡單來說，就是要將官方更新的server應用 整到 自己的應用裡面，才對得起來。

© 2024 weitusnglin. All rights reserved.
