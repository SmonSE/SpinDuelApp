<img src="images/appIcon.png" alt="Example Image" width="100"/> 

# SpinDuelApp
SpinDuel — The Ultimate Spin Challenge! Compete with friends to see who spins the longest! SpinDuel tracks your spin time with precision sensors and shares your results live via Bluetooth. Challenge yourself — Beat the record — Spin smarter!

# Build Instructions
Welcome to the SpinDuel project! This guide will walk you through building your own DIY spinner top for use with the SpinDuel app.

<img src="images/spinner_rbrw.png" alt="Example Image" width="300"/> 

## What You’ll Need
- 1x Seeed XIAO nRF52840 Sense  
- 1x LiPo Battery 3.7V, minimum 200mAh (type 502025 recommended)  
- 4x Device Screws M2x8mm Hex  
- 1x Steel Ball 6mm  
- 3D printed parts (PLA+ or PETG)  

<img src="images/spinner_parts.png" alt="Example Image" width="300"/> 

## Step-by-Step Instructions

### 1. Download Required Files
- Spinner Firmware uf2-file: [Download firmware](https://github.com/SmonSE/SpinDuelApp/tree/main/firmware)  
- 3D Printer STL files: [Download 3D models from Thingiverse](https://www.thingiverse.com/thing:7108494)
- 3D Printer STL files: [Download 3D models from Printables](https://www.printables.com/model/1374079-spinduel-diy-spinning-top-with-ios-android-app)

- 3D Printer STL files: [Download 3D models from Thingiverse](https://www.thingiverse.com/thing:7112117)
- 3D Printer STL files: [Download 3D models from Printables](https://www.printables.com/model/1377999-spinduel-diy-spinning-top-beginner-with-ios-androi)

### 2. 3D Print the Parts

Use your 3D printer with the following settings or use the sliced download files to print
- **Infill:** 25% - 30%  
- **Layer height:** 0.2 mm  
- **Supports:** Yes (grid recommended)  
- **Filament:** PLA/PLA+ or PETG (I used PLA+ from Elegoo)
- **Estimated print time:** ~3.5 hours  

### 3. Flash the Firmware
1. Connect the XIAO nRF52840 Sense to your computer.  
2. Double-press the small **rst button** quickly on the board.  
3. A USB drive will appear on your computer.  
4. Copy the `flash.uf2` file to the USB drive.
5. The XIAO SENSE will reset **automatically**.

If you receive any error message (often with Macbook) you need to copy flash.uf2 via terminal.
1. ls /Volumes
2. dot_clean /Volumes/XIAO-SENSE/
3. cp flash.uf2 "/Volumes/XIAO-SENSE/"

### 4. Assemble the Hardware
- Solder the LiPo battery to the `+` and `-` pins on the back of the board.  
- Double-check the **polarity** – incorrect wiring may damage the device.  
- Use a 3.7V LiPo battery with at least 200mAh capacity.  
- Mount the board and components using the printed parts and screws.

<img src="images/assembly overview.png" alt="Example Image" width="300"/> 

---

## App & Links
- Android APK: [Download the SpinDuel App - comming soon](https://example.com/spinduel.apk)
- Apple IOS: [Download the SpinDuel App](https://apps.apple.com/app/id6749465246)
- GitHub Repository: [View Source Code](https://github.com/SmonSE/SpinDuelApp)
- Xiao nRf52840 Sense: [Xiao nRf52840 Sense](https://www.seeedstudio.com/Seeed-XIAO-BLE-Sense-nRF52840-p-5253.html)
- Screws M2x8mm: [Amazon Screws](https://www.amazon.de/dp/B012THI93G?ref=cm_sw_r_cso_cp_apin_dp_YSDDT776W2MJ7Y2KDNH1&ref_=cm_sw_r_cso_cp_apin_dp_YSDDT776W2MJ7Y2KDNH1&social_share=cm_sw_r_cso_cp_apin_dp_YSDDT776W2MJ7Y2KDNH1&th=1)
- LiPo 200mAh battery: [LiPo Battery](https://www.amazon.de/dp/B0CSS49XFG?ref=cm_sw_r_cso_cp_apin_dp_PTYF9ETNQ7S0J1P7GSTV&ref_=cm_sw_r_cso_cp_apin_dp_PTYF9ETNQ7S0J1P7GSTV&social_share=cm_sw_r_cso_cp_apin_dp_PTYF9ETNQ7S0J1P7GSTV)
---

## About SpinDuel
SpinDuel is an interactive game where you compete based on how high and fast your custom spinner top spins. The app connects via Bluetooth to measure spin time and performance.

Developed by **Simone Eisele**.

---

Feel free to open an issue if you run into problems or have improvement suggestions. Happy building and spinning!
