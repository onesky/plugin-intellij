OneSky plugin for Android development on Intellij IDEA / Android Studio
===============

[`JetBrains Plugin Repo`](https://plugins.jetbrains.com/plugin/7607?pr=androidstudio)

# Usage

## Installation 

1.  Go to ```File``` > ```Settings``` (Windows / Linux) or ```IntelliJ IDEA``` > ```Preferences``` (Mac)
2.  Install the plugin from the IntelliJ plugin repository
3.  Search or look for ```OneSky```
4.  Click ```Download & Install```
5.  Restart the IDE

## Configuration

1.  Go to ```File``` > ```Settings``` (Windows / Linux) or ```IntelliJ IDEA > Preferences``` (Mac)
2.  Find OneSky settings (IntelliJ IDEA 13 or Android Studio): 
    - Under ```Project Settings```, select ```OneSky```
3.  Find OneSky settings (IntelliJ IDEA 14 or above): 
    - Under ```Other Settings```, select ```OneSky```
4.  Click the ```+``` button to add a new LESS profile
5.  Enter the your OneSky API key and secret, these can be found on OneSky web admin
6.  Click ```Refresh``` and select a project from the list
7.  Select the module of your Android application
8.  Click ```Apply``` or ```OK```

![settings.png](https://raw.github.com/onesky/plugin-intellij/master/Images/settings.png)

## Send Strings

1. Select ```OneSky``` from the main menu or context menu (right click any strings.xml)
2. Click ```Send Strings...```
3. Select the string resources to upload from the list
4. Optionally select ```Deprecate strings``` to deprecate the strings that cannot be found in the newly uploaded files with same filenames on server
5. Click ```Send```

![send_strings.png](https://raw.github.com/onesky/plugin-intellij/master/Images/send_strings.png)

## Sync Translations

1. Select ```OneSky``` from the main menu
2. Click ```Sync Translatioins...```
3. Select the languages you want to sync with OneSky server
4. You can see the progress of each language
5. Click ```Sync```

![sync_translations.png](https://raw.github.com/onesky/plugin-intellij/master/Images/sync_translations.png)

## Support
http://support.oneskyapp.com/
