---
tags:
  - Setting
  - contents
---
%% jQuery script %%
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
%% html2canvas script %%
<script src="script/html2canvas.js"></script>
%% Webcam script %%
<script src="script/cam.js"></script>
%% md-editor script %%
<script src="script/simplemde.min.js"></script>
<script src="script/md-editor.js"></script>
%% tts script %%
<script src="script/tts.js"></script>
%% progressbar script %%
<script>
function getCurrentProgress(){
  const firstDateOfYear = new Date(new Date().getFullYear(), 0, 1);
  const currentDate = new Date();
  return ((((currentDate - firstDateOfYear) / (1000 * 60 * 60 * 24)) * 100) / 365).toFixed(1);}
function updateUI() {const percent = getCurrentProgress();
  const barItem = document.getElementsByClassName('bar')[0];barItem.style.width = `${percent}%`;
  const counterItem = document.getElementsByClassName('value')[0];
  if (percent>100){counterItem.textContent = `100%`}else{counterItem.textContent = `${percent}%`;}}
setInterval(function() {updateUI();return arguments.callee;}(), 1000);
</script>
%% Links script %%
<script type="text/javascript">
var url = document.getElementById( 'linkshare' );
url.onchange = function() {window.open( this.options[ this.selectedIndex ].value, '_blank');
$('#linkshare').prop('selectedIndex',0);};
</script>
%% Translator script%%
<script>window.ResetTranslate = () => jQuery('#\\:1\\.container').contents().find('#\\:1\\.restore').click();</script>
<script>
    function googleTranslateElementInit() {
        new google.translate.TranslateElement({pageLanguage: 'en'},'google_translate_element');}
</script>
<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
%% share&fullcreen button script %%
<script src="script/full-share.js"></script>
%% WhiteNoise Script %%
<script type="text/javascript" src="script/WN.js"></script>
%% Preview Script %%
<script src="script/preview.js"></script>
%% Excalidraw Script %%
<script src="script/excalidraw.js"></script>
%% Excalidraw Script %%
<script src="script/graph.js"></script>
%% Study with me Script %%
<script src="script/study.js"></script>
%% Food Script %%
<script src="script/meal.js"></script>
%% Schedule Script %%
<script src="script/scheduler.js"></script>
%% Navigation bar Script %%
<script src="script/navbar.js"></script>






> <h3>This post is for the Galaxy Tab S series (One UI 6.1 ⬆️)</h3> 

![[OH.png]]

---

# Apps
## Github or Website

- Just… <a href="https://github.com/0xf104a/Mirror/releases" target="_blank" >Mirror</a>
-  Web Browser <a href="https://www.mozilla.org/en-US/firefox/all/mobile-release/" target="_blank" >Firefox</a>
    - Add-ons
        - <a href="https://addons.mozilla.org/en-US/android/addon/ublock-origin/" target="_blank" >uBlock Origin</a> (Ad-Block)
            - <a href="https://mega.nz/file/aJNDURJC#Q3C-91M4w0WeIt5EoeHlp12_FNeggGaYX-687sDivEo" target="_blank" >ublock-backup</a>
        - <a href="https://addons.mozilla.org/en-US/android/addon/video-background-play-fix/" target="_blank" >Video Background Play Fix</a> (Background Play)
        - <a href="https://addons.mozilla.org/android/addon/uaswitcher" target="_blank" >User-Agent Switcher</a> (Desktop UI on Websites)
            - Use carefully on `Phone` or `Payment`
-  File Sync <a href="https://github.com/Catfriend1/syncthing-android/releases" target="_blank" >Syncthing (Fork)</a>
-  Note-taking <a href="https://github.com/obsidianmd/obsidian-releases/releases" target="_blank" >Obsidian</a>
    - See <button id=”Link” onclick="window.open('https://filmnt.github.io/%F0%9F%9B%A0%EF%B8%8F-Setting/%F0%9F%92%A0-Obsidian', '_blank')" >💠&nbsp;Obsidian</button>
- Notion Alternatives <a href="https://github.com/anyproto/anytype-kotlin/releases" target="_blank" >Anytype</a>
-  Password Manager <a href="https://github.com/bitwarden/android/releases" target="_blank" >Bitwarden</a>
- White <a href="https://github.com/trynoice/android-app/releases" target="_blank" >Noice</a>
- Chrome Alternatives <a href="https://thorium.rocks/" target="_blank" >Thorium</a>
- Firefox Alternatives <a href="https://f-droid.org/packages/org.mozilla.fennec_fdroid/" target="_blank" >Fennec</a>
- Encrypted Calendar <a href="https://github.com/tutao/tutanota/releases" target="_blank" >Tuta Calendar</a>
- 2FA <a href="https://github.com/beemdevelopment/Aegis/releases" target="_blank" >Aegis Authenticator</a>
- Twitch Player <a href="https://github.com/crackededed/Xtra/releases" target="_blank" >Xtra</a>
- Fake <a href="https://f-droid.org/packages/cl.coders.faketraveler/" target="_blank" >Traveler</a>
- Mesh Network for SMB or Share <a href="https://tailscale.com/download/android" target="_blank" >Tailscale</a>
- Libre <a href="https://github.com/proninyaroslav/libretorrent/releases" target="_blank" >Torrent</a>
- VNC Client <a href="https://github.com/gujjwal00/avnc/releases" target="_blank" >AVNC</a>
- FOSS <a href="https://github.com/f-droid/fdroidclient/releases" target="_blank" >F-Droid</a>
- Get Updates from Website <a href="https://github.com/ImranR98/Obtainium/releases" target="_blank" >Obtainium</a>
## Play Store

-  Samsung <a href="https://play.google.com/store/apps/details?id=com.samsung.android.tvplus" target="_blank" >TV Plus</a>
-  PDF Annotation <a href="https://play.google.com/store/apps/details?id=com.orion.notein.global" target="_blank" >Notein</a>
-  PDF Viewer <a href="https://play.google.com/store/apps/details?id=com.xodo.pdf.reader" target="_blank" >Xodo</a>
- Odt Viewer <a href="https://play.google.com/store/apps/details?id=com.collabora.libreoffice" target="_blank" >Collabora Office</a>
-  Microsoft <a href="https://play.google.com/store/apps/details?id=com.microsoft.translator" target="_blank" >Translator</a>
-  iOS <a href="https://play.google.com/store/apps/details?id=com.inova.ios_14_iconpack" target="_blank" >Icon Pack</a>
    - Apply with `ThemePark` (GoodLock)
-  For `Widgets pop-up` <a href="https://play.google.com/store/apps/details?id=com.stock.widget" target="_blank" >Stock Widget</a>
    - See `One Hand Operation +`
-  File <a href="https://play.google.com/store/apps/details?id=com.alphainventor.filemanager" target="_blank" >Manager</a>

> Use `Secure Folder`(Samsung App) for Privacy.

---

# Settings 
- Notifications & Ringtones
    - <a href="https://mega.nz/file/idl2BBiI#nSnusIT2W4KINC2B_pmhRvGNyB1BMEGa9Dt-z3XTQMI" target="_blank" >Notifications</a> (162kb)
    - <a href="https://mega.nz/file/GRtAGCrD#rrLpNI7pmk-uYPe5DTmHcD_bQGGVS3TvGYbwdhEZJu8" target="_blank" >Ringtones</a> (2.3mb)
    - <a href="https://mega.nz/file/2clmGSgC#WERW4d4P5eeMGa7RD9BVeKTHC5ap_9YEJNHJzI4zXDk" target="_blank" >Wallpapers</a> (9.2mb)
    - Move to `Notifications` & `Ringtones` Folder
        - Create Folder if it doesn’t exist
    - `Settings`→ `Sounds and vibration`→ `Ringtone`/`Notification sound` → `Custom`
        - Default Ringtone: `Over the horizon`
        - Default Notification Sound: `Spaceline`
- `Developer options`
    - (Developer options) `Settings` → `About tablet` → `Software information` → Tap `Build number` several times→ Back to `Settings` 
    - `Window animation scale` → `.5x` 
    - `Transition animation scale` → `.5x`
    - `Animator duration scale` → `.5x`
    - `Minimum width`
        - `Tab` → `950dp`
        - `Fold` → `450dp`
        - `Restore`: `Settings` → `Display` → `Screen zoom`
    - (Optional) Enable `Stay awake`
        - Screen will never sleep while charging
- `Advanced` - Connections (DNS-over-HTTPS)
    - `Settings`→ `Connections`→ `More connection settings`→ `Private DNS` → `Private DNS provider hostname`
        - Set `dns.adguard-dns.com` (example)
        - There are many DNS providers…
            - <a href="https://adguard-dns.io/kb/general/dns-providers/" target="_blank" >Known DNS Providers</a>
            - <a href="https://ipleak.net/" target="_blank" >IP leak test</a>

---

# Good Guardians
- Install from `Store`
## Galaxy App Booster
- Boost up apps performance

---
## Thermal Guardian
![[TG-1.png]]
![[TG-2.png]]

---

# Good Lock 
- Install from `Store`

## NavStar
![[NV-1.png]]
---

## One Hand Operation +            
- Enable `Auto Rotate` and Check `Touch width/Size` in `Portrait/Landscape mode`
        ![[OHO-1.png]]
        ![[OHO-2.png]]
        ![[OHO-3.png]]
        ![[OHO-4.png]]
        ![[OHO-5.png]]
        ![[OHO-6.png]]
        ![[OHO-7.png]]
---
## MultiStar
- `Settings` → `Advanced features` → `Labs` and `Multi Window`
![[MS-1.png]]
![[MS-2.png]]

![[MS-3.png]]
![[MS-4.png]]
![[MS-5.png]]
![[MS-6.png]]

---
## Pentastic
- `Settings` → `Advanced features` → `S Pen`
    - You can disable `Air command` with `Modes and Routines`
![[PS-0.png]]
![[PS-1.png]]
![[PS-2.png]]
![[PS-3.png]]
![[PS-4.png]]

---
## QuickStar
![[QS-1.png]]
![[QS-2.png]]
![[QS-3.png]]
![[QS-4.png]]

---

## NotiStar
- Use `NotiStar` on `Lock Screen`
        
---

## SoundAssistant
![[SA-1.png]]
![[SA-2.png]]
![[SA-3.png]]

---

## NiceShot
![[NS-1.png]]
![[NS-2.png]]



---

# Termux (Linux on Galaxy)
![[Linux.png]]
- Could be needed later...
    - <a href="https://mega.nz/file/2clmGSgC#WERW4d4P5eeMGa7RD9BVeKTHC5ap_9YEJNHJzI4zXDk" target="_blank" >Wallpapers</a> (9.2mb)
    - <a href="https://www.xfce-look.org/s/XFCE/p/1403328/" target="_blank" >WhiteSur-Dark.tar.xz</a> (0.18mb)
    - <a href="https://www.xfce-look.org/p/1648124" target="_blank" >macOS-Monterey.tar.gz</a> (3.94mb)
    - <a href="https://www.xfce-look.org/p/1400021/" target="_blank" >Mkos-Big-Sur.tar.xz</a> (20.86mb)
> `Dimensity` or `Exynos` could leave you in trouble…
- (<font color="#ff0000">Not Optional</font>) `Error Solutions`:  Process completed (signal 9) - press Enter
    - Install `LADB` from <a href="https://github.com/hyperio546/ladb-builds/releases" target="_blank" >Here</a> (`app-debug.apk`)  
        - There are many ADB tools…
    - Connect `Wifi` and Enable `Wireless debugging` in `Developer options` 
        - (Developer options) `Settings` → `About tablet` → `Software information` → Tap `Build number` several times→ Back to `Settings` 
    - Get `port number`+`pairing code` and Enter both those values into `LADB`
        - Use multitasking options (`Split screen view` or `Pop-up view`)
        - <a href="https://youtu.be/6UO5tb_eKxY?feature=shared&t=194" target="_blank" >YouTube Guide</a>
            - See 3:14-5:40
    - Confirm connection
        - `adb devices`
    - Run the following commands
        - `adb shell "/system/bin/device_config set_sync_disabled_for_tests persistent"`
        - `adb shell "/system/bin/device_config put activity_manager max_phantom_processes 2147483647"`
        - `adb shell settings put global settings_enable_monitor_phantom_procs false`
    - Exit `LADB` and Disable `Wireless debugging`
     - You may need this…
        - `...` → `More` → `Restart` 
> - If You want to reinstall, `Termux` → `App info` → `Storage` → `Clear data` and <font color="#ff0000">Wait</font> for a while
 >   - No need to repeat the above process
- Install <a href="https://github.com/termux/termux-app/releases/download/v0.118.1/termux-app_v0.118.1+github-debug_arm64-v8a.apk" target="_blank" >Termux</a> (Ver 0.118.1) and <a href="https://github.com/termux/termux-api/releases" target="_blank" >Termux-API</a>
    - Allow permissions as following
            ![[TM-1.png]]
            ![[TM-2.png]]
- Install <a href="https://github.com/termux/termux-x11/releases" target="_blank" >X-11</a> 
    - Click ` app-arm64-v8a-debug.apk`
- Open `Termux` and Run the commands
    - For More Information, <a href="https://github.com/sabamdarif/termux-desktop" target="_blank" >Termux-Desktop</a>
      -  `[1] Generic Recommend With Hardware Accleration`
      -  `[1] XFCE`
      -  `[2] Minimalist Setup 1` or `[0] Stock` 
      - `Username`
    - It takes 10-30 minutes…
    ```shell
    curl -Lf https://raw.githubusercontent.com/sabamdarif/termux-desktop/main/setup-termux-desktop -o setup-termux-desktop && chmod +x setup-termux-desktop && ./setup-termux-desktop && pkg install -y fcitx5*
    ```
- Other Script (unstable)
   ```shell
    curl -sL https://raw.githubusercontent.com/phoenixbyrd/Termux_XFCE/main/install_xfce_native.sh -o install.sh && bash install.sh
    ```
    - `rm -rf ~/.config/xfce4/xfconf/xfce-perchannel-xml/xfwm4.xml && start`
- Minimal Script
    - See <a href="https://github.com/ar37-rs/xfce4-termux" target="_blank" >ar37-rs/xfce4-termux</a>  
> After Installation, Enter `exit` and Open `Termux:X11` - `Preferences` (Not `Termux`)
        ![[X11-1.png]]
        ![[X11-2.png]]
![[X11-3.png]]
`Clipboard sharing` can cause problem on `LibreOffice`
![[X11-4.png]]
- Just `tx11start`
    - `Back` Key = `Keyboard`, `Ctrl + C` = `Cancel`
    - Auto-Start
    ```shell
    setup-termux-desktop --change autostart 
    ```
    - (Recommend) Fix Sound Error
        - Open `File Explorer` → `/data/data/com.termux/` → Search `default.pa` and Modify `Last Line` as below
    ```shell
    load-module module-aaudio-sink
    ```
    - Get latest update
    ```shell
    setup-termux-desktop --update && cd .. && cd usr/bin && ./setup-termux-desktop
    ```
    - (Optional) For Korean…
        - Keyboard 
            - `tx11start` - `Settings` - `Fcitx 5 Configuration` → Add `Hangul` to the left
             - Modify `Trigger Input Method` in `Global Options` tab
         - Fonts
             - `Terminal` → `debian` → `sudo apt install fonts-nanum fonts-noto -y` → `exit`
> [!NOTE] S Pen Compatibility
> - You can use `S Pen Button` as `Right-Click`
> - Use `S Pen Button` with `Gesturefy` on Firefox
>     - See <button id="Link" onclick="window.open('https://filmnt.github.io/%F0%9F%9B%A0%EF%B8%8F-Setting/%F0%9F%94%A5-Firefox','_blank')"   >🔥&nbsp;Firefox</button>  Add-ons
>> - Disable `Air command` using `Modes and Routines`
>> - <font color="#ff0000">`Live-streaming` or `Termux on DeX` can consume battery even when using a high-power charger</font>
















