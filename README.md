## What does this extension do?

Show controls and information of the currently playing media in the panel.

## Features

-   Customize how the extension looks
-   Disable elements you don't want
-   Invoke different actions in many ways through mouse actions
-   Basic media controls (play/pause/next/prev)
-   Other media controls (loop/shuffle)
-   And more...

---

## Notes

-   Supports GNOME 3.36 (beta), 3.38, 40, 41, 42, 43, 44 and 45.

---

## Known issues

-   The extension does not detect when a tab is closed on some browsers. ([#35](https://github.com/sakithb/media-controls/issues/35))
-   The volume control does not work with web browsers, only with native apps.

## Reporting issues

-   Please attach a screenshot when you report something about visuals
-   Please include version of the extension, gnome version and linux distribution

---

## How to install

#### Install from extensions.gnome.org

[<img src="./images/get-ego.png" height="100">](https://extensions.gnome.org/extension/4470/media-controls/)

#### Arch Linux (AUR)

`yay -S gnome-shell-extension-media-controls` _Stable release_ (Outdated)

`yay -S gnome-shell-extension-media-controls-git` _Build of the main branch_

#### Other distributions

Install from source

-   Download "extension.zip" file from the releases tab
-   Open a terminal in the path of extension.zip
-   Install and enable the extension by executing
    <br> `gnome-extensions install extension.zip --force` <br>
    in the terminal

---

## Developing

Pull requests are welcome.

To update the translation files run ./update-translation-po-files.sh in the extensions directory after your code changes are finished. This will update the files in po folder. Then poedit (https://poedit.net/download) can be used to translate the strings. poedit can also be used to create new localization files.

## Screenshots

#### Track info menu

![Screenshot](/images/Screenshot_info_menu.png)

#### Source menu

![Screenshot](/images/Screenshot_sources_menu.png)

#### Settings page1

![Screenshot](/images/Screenshot_settings_page1.png)

#### Settings page2

![Screenshot](/images/Screenshot_settings_page2.png)

#### Settings page3

![Screenshot](/images/Screenshot_settings_page3.png)

#### Settings page4

![Screenshot](/images/Screenshot_settings_page4.png)

#### Settings page5

![Screenshot](/images/Screenshot_settings_page5.png)
