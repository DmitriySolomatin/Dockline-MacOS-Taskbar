# Set up Dockline for multiple displays and Spaces

A display is a physical screen. A Space is a macOS desktop or a full-screen workspace. Dockline lets you choose both which displays and which desktops contribute windows to a panel. Decide those two scopes first; they explain most differences between one panel's window list and another's.

This guide uses Dockline's English setting names. [Download and requirements](https://getdockline.app/) · [All Dockline guides](../README.md#practical-guides)

## Choose the windows each panel should show

Open **Settings → Displays and desktops**. Set **Show windows from displays** and **Show windows from desktops** for the view you want:

| Your preferred view | Displays | Desktops |
| --- | --- | --- |
| Every window, including work on other screens and desktops | **All displays** | **All desktops** |
| Each panel lists the windows on its own screen, across desktops | **Current display** | **All desktops** |
| Focus on the current desktop of each screen | **Current display** | **Current desktop** |

These choices filter the panel's list. They do not move your windows. For example, if a document is on the second display, the first display's panel will omit it while **Current display** is selected. [Display and desktop settings](https://getdockline.app/settings/#displays).

If you are unsure, start with **Current display** and **All desktops**. You can keep each screen's panel local to that screen while still finding windows from its other desktops. Change one scope at a time so you can see its effect.

## Keep desktop sections understandable

**Separate windows by desktop** is available with **Current display** and **All desktops**. It divides the listed windows into desktop sections. If a scope change disables the option, Dockline retains your choice for when that combination is available again.

**Show desktop labels** identifies the sections. Ordinary desktops use numbers; full-screen and Split View sections use window titles. These labels help you recognize a destination before selecting its window. [Desktop sections](https://getdockline.app/settings/#desktop-groups) · [Labels](https://getdockline.app/settings/#desktop-labels).

To create or rearrange macOS desktops themselves, use Mission Control. Apple's [Spaces guide](https://support.apple.com/guide/mac-help/mh14112/mac) covers adding desktops, switching among them and assigning apps.

## Switch desktops from the panel

Enable **Show desktop buttons** to add the desktop controls. Their order follows Mission Control and includes full-screen and Split View spaces. You can also enable **Switch desktops with the mouse wheel** while desktop buttons are on. It uses the mouse wheel over the panel; trackpad gestures retain their usual behavior. [Desktop navigation controls](https://getdockline.app/settings/#desktop-buttons).

If the panel is hidden, move the pointer to the bottom edge to reveal it. Full-screen windows remain a separate macOS mode; revealing the panel does not turn full screen into an ordinary desktop. [Panel visibility](https://getdockline.app/settings/#auto-hide).

## Understand the optional beta transfers

**Drag windows between displays** and **Drag windows between desktops** are separate **Beta** switches. Both start off. Turn on the one you want to try, then drag a window button or group to another display's panel or desktop section. A transfer that crosses both a display and a desktop needs both switches enabled.

Compatibility is still being tested. Start with an ordinary document window and check the destination before relying on the behavior in your daily workflow. The filters and desktop buttons work independently of these transfer switches. [Transfer settings and limits](https://getdockline.app/settings/#window-transfer).

## If a window seems to be missing

Check its actual display and desktop in Mission Control, then compare that location with the two scopes above. Also check whether its app is collapsed into a group. If window titles are absent across apps, follow the [Accessibility checks](window-previews-and-permissions.md).

For a [bug report](https://github.com/DmitriySolomatin/Dockline-MacOS-Taskbar/issues/new/choose), include the number of displays, the chosen scopes, the affected app, and whether the window is ordinary, minimized, full screen or in Split View. If it happened during a beta transfer, give both the starting and destination display/desktop and which transfer switches were enabled. Remove personal document titles from screenshots.

[Back to Dockline](../README.md) · [Choose a specific window](switch-between-windows-on-mac.md) · [Full settings reference](https://getdockline.app/settings/)
