# Redmi-6a-Micloud-FRP-unlock
Unlock Android Phone/Redmi 6a Micloud &amp; FRP

Need tools :

- Mediatek Driver       
- SP Flash Tool V5.1924
- LibUSB Win32        
- Mediatek Auth Bypass 

Step 1 :
Important! **Disable driver signature**

1. Install Mediatek driver
2. Install LibUSB Win32
3. Extract scatter and SP Flash Tool
4. Open SP Flash Tool, run **flash_tool.exe**
5. Load scatter from Scatter-loading file, choose **MT6765_Android_scatter.txt**
6. open MTKSecboot Disable, Click **Disable Secure Boot**
7. Turn off your phone, after that plugin your phone with good connection usb cable and hold volume up and down (do simultaneously)
8. After MTKSecboot confirm disable **MTK Secure Bypass Success**, Go back to SP Flash tool
9. Open **Format** Tab, choose **Manual Format Flash**
10. At begin address [HEX] : **0xf000000** (copy that address) and at Format Length [HEX] : **0x4000000** (copy that address) <<< (That source address from scatter)
11. Click start and Done. Enjoy!


Step 2 (**if hang logo or system destroyed**)
1. Load scatter from Scatter-loading file, choose **MT6765_Android_scatter.txt**
2. Open MTKSecboot Disable, Click **Disable Secure Boot**
3. After MTKSecboot confirm disable **MTK Secure Bypass Success**, Go back to SP Flash tool
4. Click download
5. Turn off your phone, after that plugin your phone with good connection usb cable and hold volume up and down (do simultaneously)
6. After flash, wait for 10 minutes to Language Screen, and no need step Micloud & FRP again. Done and enjoy! 
