# My TV Launcher Premium — Android TV 12

Starter source project for a custom Android TV home screen:
- Automatically discovers apps exposed through Android TV/launcher intents
- Four-column app grid, TV remote focus, clock and date
- Long-press OK on an app tile to toggle Favourite; favourites sort first
- Wallpaper button opens image picker (availability depends on the TV firmware)
- Settings shortcut and gradient fallback wallpaper

## Build from an Android phone
1. Sign in to GitHub and create a new repository.
2. Upload the files/folders in this project, keeping their directory structure.
3. Open the repository's Actions tab and run `Build Android APK`.
4. Download the `MyTVLauncher-debug-apk` artifact from the successful run and extract it.
5. Transfer `app-debug.apk` to the TV and install it. You may need to allow installation from the file app used.
6. Open My TV Launcher. Making it the default Home app depends on Hisense firmware; the Home button may still open the original launcher.

## Important
This is starter code, not a finished/tested APK and not an exact clone of the reference. The default background is a gradient; choose your own image using Wallpaper if the TV exposes a compatible document picker. Some Android TV apps are not exposed by the system. Test before setting it as default and keep the original launcher available.
