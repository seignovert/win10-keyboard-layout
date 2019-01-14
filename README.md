Mac keyboards on Windows 10
============================

Windows 10 custom layout for:
- Apple Magic Keyboard - US (qwerty)
- Logitech K811 - FR (azerty)

Created with the [Microsoft Keyboard Layout Creator](http://www.microsoft.com/en-us/download/details.aspx?id=22339) (cf. `soft/MSKLC.exe`)

Use `setup.exe` files to install the new layout. Reboot required.

Use <kbd>cmd</kbd> for <kbd>ctrl</kbd>
---------------------------------------
You need to install [Windows Server 2003 Resource Kit Tools ](https://www.microsoft.com/en-us/download/details.aspx?id=17657)
then extract `remapkey.exe` software (also available in `soft/remapkey.exe`).
Open `as administrator` (to be able to edit the registry) and drag top key and drop on bottom key:
- <kbd>ctrl</kbd> to <kbd>LeftWindows</kbd>
- <kbd>LeftWindows</kbd> to <kbd>ctrl</kbd>

Save and reboot.

Use <kbd>AltGr</kbd> for special caracters
------------------------------------------
Same as before:
- <kbd>RightAlt</kbd> to <kbd>RightWindows</kbd>

Use new keyboard as default
----------------------------
Go to `Settings > Devices > Typing > Advanced keyboard settings > Override for default input method`. Reboot required.