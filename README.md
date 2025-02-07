# URLEZFX
A versatile task for Android's Tasker and an equivalent Shortcut for iOS designed to automatically modify URLs from various social media and video platforms to custom or alternative domains. This utility can be particularly useful for:

- **Privacy:** Redirecting links to privacy-focused alternatives.
- **Content Access:** Accessing content through different, possibly less restricted, domains.
- **Testing:** Checking how URLs behave with different domain names.

## Features

- **Input Prompt:** Asks the user to input a URL.
- **URL Modifications:**
  - Converts Twitch clips to `fxtwitch.seria.moe`.
  - Replaces Twitter with `twitterez.com`.
  - Redirects Reddit to `redditez.com`.
  - Switches Instagram to `instagramez.com`.
  - Changes YouTube links to `piped.video` for ad-free viewing.
  - Modifies Snapchat links to `snapchatez.com`.
  - Alters TikTok URLs to `tiktokez.com`.
  - Transforms X (formerly Twitter) links to `twitterez.com`.
- **Display:** Shows the modified URL via a flash message on Tasker or through a notification/action sheet on iOS Shortcuts.

## Usage

### For Tasker (Android):

- **Import into Tasker:** Use the XML provided to import this task directly into Tasker.
- **Integration:** Link this task with a profile in Tasker (like a button tap or a notification click) to use it in various contexts.

- **Creating a Widget / Shortcut**
  - Click and hold in an empty space on the Android home screen, until a dialog appears.
  - Select Widgets or Shortcuts
  - Select Task (Widgets only)
  - Pick URLEZFX


### For iOS Shortcuts:

- **Import into Shortcuts:** Download the `.shortcut` file from this repository and open it with the Shortcuts app to import.
- **Activation:** Add the shortcut to your home screen, use Siri, or run it from within the Shortcuts app.

## Installation

- **Tasker:** Download the `.xml` file from this repository. In Tasker, navigate to **Tasks** > **+** > **Import** and select the downloaded file.
- **iOS Shortcuts:** Get the `.shortcut` file from this repo and import it into the Shortcuts app.

## Customization

- **Tasker:** You can modify the regex patterns or add new ones to include more URL transformations. Adjust the flash message duration or change it to a different action for displaying the result.
- **iOS Shortcuts:** Adjust the actions or add more URL substitutions directly within the Shortcuts app's interface.

## Notes

- Ensure your Tasker or iOS Shortcuts version supports all the features used. This task has been tested on iOS Shortcuts version 18.3
- Regex patterns are sensitive; test thoroughly after modifications to ensure they match and replace as expected.

## Contribution

Feel free to fork this repository, modify the tasks to include more URL modifications, or improve existing ones. Pull requests are welcomed for:

- New URL transformations for either platform.
- Bug fixes in regex patterns or functionality.
- Enhancements to the user experience or automation process.

## License

GNU General Public Licece v3.0
