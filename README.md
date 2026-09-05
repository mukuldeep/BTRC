# BTRC
Bluetooth Remote Control Pro User Manual

Universal Serverless Bluetooth Remote with Keyboard & Mouse. Turn your phone into a powerful Bluetooth serverless Remote for Android TV, Smart TV, PC, Mac, Cameras on Android, IOS, Linux, Windows, TV Os. Control your TV, Laptop, PC media smoothly with a fast and stable Bluetooth connection. Navigate apps, control volume, change channels, and manage media — all directly from your phone. Serverless remote control using only bluetooth, works completely offline mode. No server need to run on host device. Easy to swap devices. No more slow or limited remotes for your TV.

https://play.google.com/store/apps/details?id=com.offlinew.btrc

### ADVANCED Support for customized Buttons

This app supports 2 Bytes keycode. Key code for some of the operations are as listed below

| Key Code | Function |
| --- | --- |
| `0x30 0x00` | POWER |
| `0x32 0x00` | SLEEP |
| `0x6F 0x00` | BRIGHTNESS_UP |
| `0x70 0x00` | BRIGHTNESS_DOWN |
| `0xE9 0x00` | VOLUME_UP |
| `0xEA 0x00` | VOLUME_DOWN |
| `0xE2 0x00` | MUTE |
| `0xE5 0x00` | BASS_BOOST |
| `0xCD 0x00` | PLAY_PAUSE |
| `0xB7 0x00` | STOP |
| `0xB5 0x00` | NEXT_TRACK |
| `0xB6 0x00` | PREV_TRACK |
| `0xB3 0x00` | FAST_FORWARD |
| `0xB4 0x00` | REWIND |
| `0xB2 0x00` | RECORD |
| `0xB8 0x00` | EJECT |
| `0x40 0x00` | MENU |
| `0x41 0x00` | MENU_PICK (Often "OK") |
| `0x42 0x00` | MENU_UP |
| `0x43 0x00` | MENU_DOWN |
| `0x44 0x00` | MENU_LEFT |
| `0x45 0x00` | MENU_RIGHT |
| `0x46 0x00` | MENU_ESCAPE |
| `0x23 0x02` | HOME |
| `0x24 0x02` | BACK |
| `0x21 0x02` | SEARCH (Voice/Text Search) |
| `0x2A 0x02` | RECALL_LAST (Recent Apps) |
| `0x60 0x02` | DATA_ON_SCREEN (Info button) |
| `0x94 0x01` | LAUNCH_BROWSER |
| `0x8A 0x01` | LAUNCH_EMAIL |
| `0x92 0x01` | LAUNCH_CALC |
| `0x83 0x01` | LAUNCH_MEDIA |
| `0x89 0x01` | APP_LAUNCH_TV |
| `0xA2 0x01` | APP_LAUNCH_MOVIES |
| `0x93 0x01` | APP_LAUNCH_MUSIC |
| `0xB1 0x01` | LAUNCH_NETFLIX |
| `0xB3 0x01` | LAUNCH_YOUTUBE |
| `0xB4 0x01` | LAUNCH_HULU |
| `0xB5 0x01` | LAUNCH_SPOTIFY |
| `0xB7 0x01` | LAUNCH_PRIME_VIDEO / RED_BUTTON |
| `0xB8 0x01` | LAUNCH_DISNEY_PLUS / GREEN_BUTTON |
| `0xBC 0x01` | LAUNCH_HBO_MAX |
| `0xBE 0x01` | LAUNCH_APPLE_TV |
| `0xB9 0x01` | YELLOW_BUTTON |
| `0xBA 0x01` | BLUE_BUTTON |
| `0x9C 0x00` | CHANNEL_UP |
| `0x9D 0x00` | CHANNEL_DOWN |
| `0x1A 0x02` | LAST_CHANNEL (Recall) |
| `0x8D 0x00` | GUIDE (EPG - Electronic Program Guide) |
| `0xBD 0x01` | INFO (Program Information) |
| `0x1B 0x02` | INPUT_SOURCE (Cycle through HDMI/TV/AV) |
| `0x96 0x01` | SETTINGS (Hardware Settings) |
| `0x61 0x00` | SUBTITLES (Closed Captioning - CC) |
| `0xBB 0x01` | AUDIO_LANG (Change Audio/Language track) |

Other than these codes some of the known codes used by many electronics devices are as listed below 

| Key Code | Function | Description / Notes |
| --- | --- | --- |
| `0x31 0x00` | RESET | Hard System Reset |
| `0x35 0x00` | ILLUMINATION | Display Illumination Toggle |
| `0x65 0x00` | SNAPSHOT | Take Screenshot / Capture |
| `0x67 0x00` | PIP_TOGGLE | Picture-in-Picture Toggle |
| `0x68 0x00` | PIP_SWAP | Picture-in-Picture Swap Screens |
| `0x6D 0x00` | ASPECT_RATIO | Toggle Aspect Ratio (16:9 / 4:3) |
| `0x6E 0x00` | MODE_3D_SELECT | Toggle 3D Display Mode |
| `0x72 0x00` | DISPLAY_BACKLIGHT_TOGGLE | Turn Screen Backlight On/Off |
| `0x79 0x00` | KB_BRIGHTNESS_UP | Keyboard Backlight Brightness + |
| `0x7A 0x00` | KB_BRIGHTNESS_DOWN | Keyboard Backlight Brightness - |
| `0x80 0x00` | SELECTION | Select Item / Focus |
| `0x83 0x00` | RECALL_LAST_CHANNEL | Switch to Last Channel |
| `0x88 0x00` | MEDIA_SELECT_COMPUTER | Switch Input to PC |
| `0x8B 0x00` | MEDIA_SELECT_DVD | Switch Input to DVD/Blu-ray |
| `0x8F 0x00` | MEDIA_SELECT_GAMES | Switch Input to Game Console |
| `0x94 0x00` | QUIT | Exit Active Application |
| `0x95 0x00` | HELP | Open Help / FAQ Overlay |
| `0xB0 0x00` | PLAY | Explicit Play (Separate from Pause) |
| `0xB1 0x00` | PAUSE | Explicit Pause (Separate from Play) |
| `0xB9 0x00` | RANDOM_PLAY | Shuffle / Random Playback |
| `0xBC 0x00` | REPEAT | Repeat Track / Playlist |
| `0xCC 0x00` | STOP_EJECT | Combined Stop & Eject Disc |
| `0x01 0x01` | AL_CONSUMER_CONTROL | Launch Main Consumer App |
| `0x81 0x01` | LAUNCH_AL_CHECKS | Launch Financial / Accounting App |
| `0x82 0x01` | LAUNCH_CONTROL_PANEL | Open System Settings / Control Panel |
| `0xAE 0x01` | LAUNCH_AL_KEYBOARD_LAYOUT | Toggle Keyboard Input Language |
| `0x1A 0x02` | RECALL_LAST | Quick App Switcher |
| `0x22 0x02` | AC_SEARCH | Global System Search / Spotlight |
| `0x25 0x02` | AC_FORWARD | Browser/App Forward Navigation |
| `0x26 0x02` | AC_STOP | Stop Page Load / Operation |
| `0x27 0x02` | AC_REFRESH | Reload Page / View |
| `0x28 0x02` | AC_BOOKMARKS | Open Favorites / Bookmarks |


### Designed for TV & Android TV Users

- Full-featured Android TV Remote
- Smooth navigation & media controls
- Quick access buttons
- Easy pairing via Bluetooth
- Works with Smart TVs, TV boxes & PCs

Perfect for streaming, browsing, YouTube, Netflix, and everyday TV control.

### Bonus: Keyboard & Mouse Included

Need to type or move a cursor?

- Built-in Bluetooth Keyboard
- Smooth Bluetooth Mouse / Air Mouse
- Fast text input on TV
- Great for search, login, and browsing

No more typing with a TV remote D-pad.

### One App. Complete Control.

- TV Remote
- Media Controller
- Wireless Keyboard
- Wireless Mouse


All in one lightweight and reliable app.

### Works as Remote for Popular Smart TV Brands

Looking for a remote for your TV brand? This app works as a Bluetooth remote replacement for many Smart TVs and Android TVs, including:

 - Samsung TV Remote
 - LG TV Remote
 - Sony TV Remote
 - Mi TV Remote
 - OnePlus TV Remote
 - TCL TV Remote
 - Panasonic TV Remote
 - Philips TV Remote
 - Vu TV Remote
 - Realme TV Remote
 - Hisense TV Remote
 - Motorola TV Remote

If your TV supports Bluetooth, this app can work as your wireless remote control.No IR required. No WiFi dependency. Direct Bluetooth connection. Download now and turn your phone into the universal Bluetooth TV Remote.
