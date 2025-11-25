# README

1. 安裝 rime 輸入法
    - Windows: [Rime for Windows](https://rime.im/download/)
    - Linux
        ```bash
        sudo apt update && sudo apt install ibus-rime -y
        ```

2. 下載客製化設定檔案到 Rime 使用者目錄
    - Windows: `%APPDATA%\Rime`
    - Linux: `~/.config/ibus/rime`

    1. 下載 rime-ice 專案
        ```bash
        git clone git@github.com:iDvel/rime-ice.git <rime_setting_directory>
        ```

    2. 下載我的設w定
        - lua 目錄的 `corrector.lua` 可以從 rime-ice 專案覆蓋或是合併
        ```bash
        git clone git@github.com:ycpss91255/rime-ice.git <rime_setting_directory>
        ```

4. 重新部署 rime 輸入法
5. Enjoy it!
