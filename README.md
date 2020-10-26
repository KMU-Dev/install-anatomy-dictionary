# Install Anatomy Dictionary

![GitHub Releases](https://img.shields.io/github/downloads/KMU-Dev/install-anatomy-dictionary/latest/total?color=brightgreen)

Install anatomy dictionary to google chrome custom type checking.

## Notice :heavy_exclamation_mark::heavy_exclamation_mark:

There are some bugs when you install the program at the first time.
Please make sure you turn off Chrome before installing and try until the console show "Successfully install anatomy dictionary!!".

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
