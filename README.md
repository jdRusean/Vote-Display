# Vote Display — Vote Stream Studio

A Windows desktop app for displaying Google Forms voting results during livestreams.

## Download

Download **Vote Stream Studio Desktop Windows.zip** from [the latest release](https://github.com/jdRusean/Vote-Display/releases/latest).

Extract the **entire ZIP**, open the extracted folder, and launch **Vote Stream Studio.exe**. No programming knowledge, Apps Script, or Node.js installation is required.

Download the Windows ZIP under **Assets**. The **Code → Download ZIP** and automatically generated source archives contain repository documentation, not the desktop application.

## Request Google sign-in access

**Before connecting Google Sheets, email [cedidags@gmail.com](mailto:rusnogadi@gmail.com) with the Google email address you intend to use.**

The app currently uses Google's OAuth **Testing** mode. Only Google accounts added to its approved test-user list can authorize Google Sheets access. Wait for confirmation that your account has been added, then sign in with that same account.

Your account must also own or have permission to view your Form's response Sheet. Tester approval does not grant access to someone else's spreadsheet.

You do not need to create a Google Cloud project or configure OAuth yourself. While the app remains in Testing mode, Google authorization expires after seven days and you will need to reconnect. See [Google's testing limits](https://support.google.com/cloud/answer/15549945).

CSV previews can be used without Google sign-in. CSV imports are snapshots and do not update live.

## Getting started

1. Link your Google Form's responses to a Google Sheet.
2. Sign in to the app using your approved Google account.
3. Connect the response Sheet and create an overlay.
4. Choose the question whose results you want to display.
5. Add all answer choices, portraits, and display settings. Adding every choice lets the overlay show zero votes before voting starts.
6. Choose **Health bars** or **Portrait cards**. Under **Appearance**, choose container and font colors and optionally enlarge leading choices.
7. Wait for **All changes saved**. Click a saved tile to edit it, or use **Open overlay** to display it.
8. For OBS, copy the overlay URL into a **Browser Source** and place that source above your game capture.

Keep Studio running on the same computer as OBS. An OBS Browser Source can show results while another app covers the floating window. A Display Capture only shows what is visible on your monitor.

Google Forms controls whether viewers may submit multiple responses. The app counts submitted response rows. Allow time for Forms to write new responses to Sheets.

## Features

- Live Google Sheets voting results and multiple saved overlays.
- Portrait cards and health-bar displays.
- Transparent floating overlays and OBS Browser Source support.
- Custom container and font colors.
- Optional larger leading entries, with equal emphasis for tied leaders.
- Editable titles and selectable on-screen details.
- Dark, Ube, and Café themes.
- Guided practice tutorial with simulated votes.

## Desktop controls

Hover near the top of a floating overlay for its toolbar. Studio's **Overlay windows** panel also provides window controls. **Ctrl + Alt + O** brings Studio forward and recovers click-through controls.

Closing the main Studio window closes its floating overlays and stops updates. Settings, portraits, and saved Google authorization are stored in your Windows user profile; they are not included in the shared download.

## Contact

For tester access, questions, or feedback: **[cedidags@gmail.com](mailto:rusnogadi@gmail.com)**.

This is an early-access desktop test build. This repository distributes the packaged app and documentation; application source code is not included.
