# Switch between windows of the same app on Mac

If you have three documents open in the same app, switching to that app is only the first step. You still need to choose a document. macOS includes keyboard and overview tools for this; Dockline adds a panel of named window buttons.

This guide uses the English labels in Dockline. [Download and requirements](https://getdockline.app/) · [All Dockline guides](../README.md#practical-guides)

## Start with the macOS controls

| Task | Built-in control |
| --- | --- |
| Move to another app | **Command–Tab** |
| Cycle through windows in the current app | **Command–grave accent** (the backtick key on a US keyboard) |
| See the current app's windows together | **Control–Down Arrow** for App Exposé |
| See windows on the desktop and the Spaces bar | **Control–Up Arrow** for Mission Control |

Keyboard layouts and customized shortcuts can change the keys you use. Apple documents the [keyboard shortcuts](https://support.apple.com/en-us/102650) and [Mission Control controls](https://support.apple.com/guide/mac-help/mh35798/mac).

These are useful starting points if you mainly navigate with a keyboard or want a temporary overview. A named taskbar is useful when you want the window choices to stay visible while you work.

The [Windows-style taskbar for Mac guide](https://getdockline.app/guides/windows-style-taskbar-for-mac/) compares the Dock, Mission Control, App Exposé and persistent window buttons, with a three-window test to help you choose.

## Select a window by title in Dockline

1. Open two ordinary document or browser windows. Give them distinct titles or content so you can tell them apart.
2. Allow **Accessibility** in Dockline's **Settings → Permissions**. This gives Dockline access to window titles and window controls. See the [permission steps](window-previews-and-permissions.md) if the windows are absent.
3. Find the window's title on the panel and click its button.
4. If the app's windows have collapsed into one button, open the group list and select the individual window there. Optional previews can help distinguish windows with similar names.

Dockline represents windows. Two tabs inside one browser window still belong to that one window; use the browser's tab controls to move between them.

## Choose how much grouping you want

Open **Settings → Windows and groups**. Two controls affect different parts of the panel:

| Control | Effect |
| --- | --- |
| **Combine app windows** | Keeps separate window buttons inside a shared background with one app icon. |
| **Collapse windows into one button → Never** | Keeps individual window buttons. A crowded panel has less room for each title. |
| **Collapse windows into one button → When space is limited** | Keeps separate buttons while there is room and groups them as the panel fills. |
| **Collapse windows into one button → Always** | Uses one button for the app's group, with individual windows in its list. |

For a first comparison, try **Never** with two windows, then **Always** with the same two. Pick the arrangement that makes the documents easier for you to find. The [windows and groups reference](https://getdockline.app/settings/#tasks) explains these controls.

## When the result is unexpected

If clicking the window that is already active minimizes it or returns to another window, check **Active window click** in the same section. Its options are **Minimize / restore**, **Previous window** and **Do nothing**. [Active-window behavior](https://getdockline.app/settings/#active-window-click).

If a window on another display or Space is missing, check the display and desktop filters before changing permissions. The [displays and Spaces guide](displays-and-spaces.md) explains which combinations include that window.

If a problem remains, [report it](https://github.com/DmitriySolomatin/Dockline-MacOS-Taskbar/issues/new/choose) with the app and Dockline versions, the grouping choice, and whether the window was minimized, full screen or on another desktop. Use sample documents so the report does not expose personal window titles.

[Try Dockline](https://getdockline.app/) · [Window previews and permissions](window-previews-and-permissions.md) · [Settings reference](https://getdockline.app/settings/)
