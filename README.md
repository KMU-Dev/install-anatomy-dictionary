# Install Anatomy Dictionary

![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/KMU-Dev/install-anatomy-dictionary)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/KMU-Dev/install-anatomy-dictionary)
![GitHub All Releases](https://img.shields.io/github/downloads/KMU-Dev/install-anatomy-dictionary/total?color=brightgreen)
![GitHub](https://img.shields.io/github/license/KMU-Dev/install-anatomy-dictionary)

Install anatomy dictionary to google chrome custom type checking.

## Notice :heavy_exclamation_mark::heavy_exclamation_mark:

1. **When running this app in computer in the classroom, make sure you have uninstalled F-secure or it will block downloading.**
2. **Please go to "chrome://settings/editDictionary" to remove old anatomy dictionary before installing new histology dictionary when installing this app in your own computer.**

## Install

Go to the [release page](https://github.com/KMU-Dev/install-anatomy-dictionary/releases/latest) to download the latest executables.

## Function

This app will import the first online anatomy test dictionary file to Google Chrome's built in type checking system.
Enjoy it. :wink::wink:

## Advanced Usage

To enable Chrome's typo fixing, follow the steps below:

1. Go to Chrome Language settings (chrome://settings/languages), which is in the "advanced" section of side bar in the settings page.
Select the "Enhanced spell check" in the "spell check" section.

2. In wm's test page, Press F12 to open Chrome DevTools.
In the top navigation bar, click "Elements" tab, and then in the right window, click "Event Listeners" tab.
Expand the "contextmenu" list and "Remove" all the listeners inside.

    In short: `DevTools > Elements > Event Listeners > contextmenu > Remove all listeners`

3. All done!! When you type something wrong, you can select the red underlined word and click your right mouse.
Any possible fixing words will show up in the menu.

## Contributing

1. Clone the project using

    ```git clone https://github.com/KMU-Dev/install-anatomy-dictionary.git```

2. Run the following command to generate bindata.go file

    ```go generate```

3. Build the app

    ```go build```
