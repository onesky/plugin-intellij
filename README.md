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
2.  Find OneSky settings (IntelliJ IDEA 13):
    - Under ```Project Settings```, select ```OneSky```
3.  Find OneSky settings (IntelliJ IDEA 14 or above or Android Studio):
    - Under ```Other Settings```, select ```OneSky```
4.  Enter the your OneSky API key and secret, these can be found on OneSky web admin
5.  Click ```Refresh``` and select a project from the list
6.  Select the module of your Android application
7.  Click ```Apply``` or ```OK```

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
5. Optionally select ```Copy resources for deprecated locales support```, the plugin will copy resources to support deprecated locales (e.g. copy Hebrew 'he' to 'iw'). For more information, please visit [Android - Locale - Class Overview](http://developer.android.com/reference/java/util/Locale.html)
6. Click ```Sync```

![sync_translations.png](https://raw.github.com/onesky/plugin-intellij/master/Images/sync_translations.png)

## Support
http://support.oneskyapp.com/

## Helpful articles
[ How to find API key ](http://support.oneskyapp.com/solution/categories/74754/folders/150388/articles/89104-how-to-find-your-api)

[More from here](http://support.oneskyapp.com/solution/categories)

