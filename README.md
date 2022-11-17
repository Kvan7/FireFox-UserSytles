# FireFox-UserSytles

My own personal userContent css for my firefox browser. Just to make personal changes and pages look better IMO.

## Installing

Installing follows these general steps:

1. Copy files to `AppData/Roaming/Mozilla/Firefox/Profiles/xxxxxxx.default-release/chrome`
2. Enable userstyles in Firefox

Copy the `img` folder and the `userContent.css` to your `chrome` folder.
This folder is located at `AppData/Roaming/Mozilla/Firefox/Profiles/xxxxxxx.default-release/chrome`. If the chrome folder is not is your `default-release` then create it.

After copying the files to `chrome`, open Firefox and go to `about:config` in your search bar. You will be warned to proceed with caution, accept and continue. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` in the search box at the top. There should be one option showing. Ensure that `toolkit.legacyUserProfileCustomizations.stylesheets` is set to **`true`**. If no option for this shows up, ensure that the checkbox to the right of the search bar, labeled "Show only modified preferences" is **Unchecked**.

Restart Firefox and styles should be enabled

For more information can be found on [Winaero's Site](https://winaero.com/enable-loading-userchrome-css-usercontent-css-firefox/)
