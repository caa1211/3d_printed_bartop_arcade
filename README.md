# 3D列印樹莓派街機框體 

![image](https://user-images.githubusercontent.com/1962079/118118085-0709ca00-b41f-11eb-91f0-dfa96a037d11.png)
![image](https://user-images.githubusercontent.com/1962079/118124310-fd389480-b427-11eb-8513-bbab23090852.png)


# 框體列印
* 使用此模型列印 [simplyRetro D8 by Geaz](https://www.thingiverse.com/thing:4295854)
* 推薦使用 [SpiderMaker 消光 PLA](https://www.3dspidermaker.com/categories/pla-matte-series)，台灣製造，高品質的3d列印線材。
* [功放旋鈕](https://www.thingiverse.com/thing:3405786)

# 零組件清單 (BOM)
* 樹莓派4B (2gb or 4gb)
* [8吋螢幕 HJ080IA-01E](https://item.taobao.com/item.htm?id=638855824682) (174*136mm)
* [螢幕驅動板 單hdmi 5v](https://item.taobao.com/item.htm?id=638855824682)
* [焊好的喇叭](https://item.taobao.com/item.htm?id=639400661884)
* [功率放大器 可USb供電](https://item.taobao.com/item.htm?id=555919174180)
* [街機搖杆芯片 2P線x10 5p線x1](https://item.taobao.com/item.htm?id=525916540740)
* [搖杆](https://item.taobao.com/item.htm?id=575008844746) (可換三和)
* [24mm按鈕 x 8](https://item.taobao.com/item.htm?id=617646767295) (可換三和)
* [螺絲 m3x8 x 12](https://detail.tmall.com/item.htm?id=602980250427)
* [螺絲 m2.5x6 x 4](https://detail.tmall.com/item.htm?id=617769020674) (固定樹莓派)
* [m3腳墊 16mm圓](https://detail.tmall.com/item.htm?id=615675530996)
* [USB 20cm 彎頭 x 2](https://item.taobao.com/item.htm?id=596748753207) (爭取框體內空間)
* 鐵氟龍膠帶或[絕緣膠帶](https://detail.tmall.com/item.htm?id=35302386191)
* [USB type-c 對 type-a 帶開關接線](https://item.taobao.com/item.htm?id=605017376533) (樹莓派供電)
* Micro USB 對 type-a 長接線 (螢幕驅動板供電)
* Micro USB 對 type-a 短接線 (功率放大器供電)
* 小米2口USB充電器 (同時供電樹莓派(5v3a)與螢幕驅動板(5v2a)
* micro Hdmi-hdmi 公對公接線 (愈短愈節省空間)
* 3.5mm音頻公對公接線
* microSD卡 (64或256gb)
* 包線管 (1~2m)


# 零組件清單 (額外部分)
* [三和搖杆](https://item.taobao.com/item.htm?id=638695112508)
* [三和按鈕 24mm x 8](https://item.taobao.com/item.htm?id=545996014796)
* [木製搖杆頭](https://item.taobao.com/item.htm?id=585770082174)

# 組裝

> 組裝過程需要H2.0內6角螺絲起子

![image](https://user-images.githubusercontent.com/1962079/118122815-f3159680-b425-11eb-9ce2-a78e37b24ced.png)

> 先行測試螢幕是否正常

![image](https://user-images.githubusercontent.com/1962079/118122973-29ebac80-b426-11eb-9660-463a54f537aa.png)

> 螢幕背面貼鐵氟龍或絕緣膠帶

![image](https://user-images.githubusercontent.com/1962079/118123008-340dab00-b426-11eb-95af-97f64ba76d95.png)

![image](https://user-images.githubusercontent.com/1962079/118122929-20624480-b426-11eb-92eb-ac4aa4462ad9.png)
![image](https://user-images.githubusercontent.com/1962079/118123048-41c33080-b426-11eb-8caf-267ef7245bbd.png)
![image](https://user-images.githubusercontent.com/1962079/118122835-fdd02b80-b425-11eb-932a-c4d0a6a243d6.png)
![image](https://user-images.githubusercontent.com/1962079/118122862-04f73980-b426-11eb-9eb0-d7420c961d94.png)
![image](https://user-images.githubusercontent.com/1962079/118122883-0d4f7480-b426-11eb-899e-32fc1bbc1251.png)
![image](https://user-images.githubusercontent.com/1962079/118122906-15a7af80-b426-11eb-9a02-6bfe34bd4818.png)

> 使用包線管整理電源線

![image](https://user-images.githubusercontent.com/1962079/118123964-88655a80-b427-11eb-8659-f192703af980.png)

> 最後鎖上腳墊

![image](https://user-images.githubusercontent.com/1962079/118124208-da0de500-b427-11eb-9a7e-4365331e0dc0.png)


# 軟體安裝
* 推薦以下三擇一
  - [官方 Retropie 乾靜系統](https://retropie.org.uk/download/)
  - [64gb Wolfanoz 含測試rom 6000個](https://www.arcadepunks.com/new-pi-4-retro-gaming-64gb-build-20-classic-gaming-systems/)
  - [256gb Wolfanoz 含rom 13000個](https://www.arcadepunks.com/256gb-fully-loaded-supreme-pro-raspberry-pi-4-image-from-wolfanoz/)
* 使用 [Win32 Disk Imager](https://sourceforge.net/projects/win32diskimager/) 寫入即可

# wifi 設定
* 依照[官方文件](https://retropie.org.uk/docs/Wifi/)設定，請記得要設定 WLAN Country 為 **TW**，否則 wifi 設定會失敗。
```
NOTE: In order to use the WiFi on the new Raspberry Pi 3 Model B+,
you will need to first configure the WLAN Country via raspi-config. 
It’s under menu 5 Localisation options in raspi-config.
You can start raspi-config from the RetroPie menu in EmulationStation or from the command line with sudo raspi-config.
```
* wifi 設定過程中需要輸入密碼，建議先準備藍芽小鍵盤或使用USB鍵盤。

# 藍芽鍵盤連線
* [官方文件](https://retropie.org.uk/docs/Bluetooth-Controller/)
![image](https://user-images.githubusercontent.com/1962079/118124784-a8e1e480-b428-11eb-85ea-d17055d88af8.png)

# PS3藍芽手把安裝
* [官方文件](https://retropie.org.uk/docs/PS3-Controller/)目前推薦 sixaxis 驅動，而 ps3controller 驅動對非原廠的 PS3 手把支援性可能較佳。
* sixaxis
  - 1. 先至RetroPie Setup 選 Manage packages 再選 driver
  - 2. 選 sixaxis 再選 Install from source
  - 3. 裝完後去同藍芽連線，不同的是在掃描藍芽的過程中，需要將PS3手把照畫面上指示拔插一次。
  - 4. 退回到 EmulationStations，配置 PS3 手把按鈕對應

# 螢幕無輸出
* Pi4 有兩個 hdmi port，此情況優先換hdmi port 試試，官方預設以 hdmi0 port 輸出，為電源輸入旁邊的 hdmi 孔，客制化 image 可能會有變更。

# 螢幕比例跑掉
* 若為樹莓派輸出問題，請將 SD 卡插入 windows 系統，修改 config.txt 中的 hdmi_mode 依照螢幕的規格及[此文件](https://elinux.org/RPiconfig#Video_mode_options)給予正確設定，例如 HJ080IA-01E 是 1024x768-60Hz-4:3
正確設定為
```
hdmi_mode=16
```
* 若為遊戲輸出的比例問題，遊戲中按下 function key + x 進入 retroarch 設定，選 Settings -> Video -> Scaling -> Aspect Ration，內有多種比例可調整，若要存為全域設定，進 Retroarch 的 Main menu 的 Configuration File，選擇 Save Current Configuration。


# 關於我
* FB: caa1211
* Mail: caa1211@gmail.com
