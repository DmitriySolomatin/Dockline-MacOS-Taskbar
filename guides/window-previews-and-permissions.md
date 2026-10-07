# Fix missing windows or window previews in Dockline

Window controls and preview images use different macOS permissions. Start with the symptom you can see, then check the relevant setting. Opening a permission page alone does not grant access.

[Download and requirements](https://getdockline.app/) · [All Dockline guides](../README.md#practical-guides)

| What you see | Check first |
| --- | --- |
| Dockline cannot list or activate ordinary app windows | **Accessibility** in **Settings → Permissions**. |
| Titles appear, but the group list has no images | **Window previews** and **Screen Recording**. |
| A window is missing only on another display or desktop | The display and desktop filters in **Displays and desktops**. |
| The panel is unavailable after Trial | Your access status in **Settings → Licensing**. |

## Allow Dockline to read and control windows

1. Open **Settings → Permissions** in Dockline and find **Accessibility**.
2. Choose **Open macOS Settings**. In **Privacy & Security → Accessibility**, enable Dockline.
3. If it is missing from the list, use the plus button to add Dockline from Applications, or drag the app icon offered in Dockline's permission card into the list. Enable its switch.
4. Return to Dockline and choose **Check again**. Check that the permission is shown as **Allowed**.
5. Open an ordinary document window and try selecting it from the panel.

Accessibility enables window titles and actions such as activation, minimization and closing. Apple explains how to [review Accessibility access](https://support.apple.com/guide/mac-help/mh43185/mac). Dockline's [Accessibility reference](https://getdockline.app/settings/#accessibility) describes its controls.

## Enable preview images separately

Previews are optional and start off. You can keep using the group list by window title without them.

1. In **Settings → Windows and groups**, turn on **Window previews**.
2. If access is still missing, choose **Allow Screen Recording** or **Open macOS Settings** in its permission controls.
3. In **Privacy & Security → Screen & System Audio Recording**, enable Dockline's screen access. macOS may ask you to reopen Dockline; follow that prompt if it appears.
4. Return to Dockline and use **Check again** when available. Open an app's group list to check the images beside its window titles.

For a simple check, open two ordinary document windows with different content. In **Windows and groups**, temporarily choose **Collapse windows into one button → Always**, then open that group. Restore your preferred grouping choice afterward.

Dockline prepares available preview snapshots in the background. Preview images are not saved. See [Window previews](https://getdockline.app/settings/#window-previews) and Apple's explanation of [Screen & System Audio Recording access](https://support.apple.com/guide/mac-help/mchld6aa7d23/mac).

## Check whether a window is filtered out

In **Settings → Displays and desktops**, **Current display** hides windows located on another display from that panel. **Current desktop** limits the list to the current desktop. Temporarily select **All displays** and **All desktops** to check whether this explains a missing window, then restore your preferred choices. [Filter examples](displays-and-spaces.md).

A browser tab is part of its browser window. A dialog or floating utility surface may also behave differently from an ordinary document window. Include the kind of window when describing a problem.

## If the problem continues

Open **Settings → Diagnostics** and choose **Refresh status**. Note the affected app, your Dockline and macOS versions, the permission status, and the shortest sequence that reproduces the problem. State whether one app is affected or several, and whether the window is minimized, full screen or on another display or desktop.

You can inspect **View report** before deciding what to share. Review screenshots and diagnostic text for personal window titles, file paths, email addresses and account information. Dockline does not send the diagnostic report automatically. [Diagnostics reference](https://getdockline.app/settings/#diagnostics).

[Report a reproducible bug](https://github.com/DmitriySolomatin/Dockline-MacOS-Taskbar/issues/new/choose) or [ask a usage question](https://github.com/DmitriySolomatin/Dockline-MacOS-Taskbar/discussions/categories/q-a). Purchase and account questions go privately to [help@getdockline.app](mailto:help@getdockline.app); never send passwords, sign-in codes or license keys.

[Back to Dockline](../README.md) · [Official support](https://getdockline.app/support/) · [Release history](https://getdockline.app/updates/)
