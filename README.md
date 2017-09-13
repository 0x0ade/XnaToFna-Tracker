# XnaToFna-Tracker
Game status tracking repository for XnaToFna. Search for your game in the [issues](https://github.com/0x0ade/XnaToFna-Tracker/issues) or [create a new issue](https://github.com/0x0ade/XnaToFna-Tracker/issues/new) if you want to share the status of a game running via XnaToFna.

[**For a stable build of XnaToFna, click here.**](https://github.com/0x0ade/XnaToFna/releases)

[**For issues with XnaToFna itself, click here.**](https://github.com/0x0ade/XnaToFna/issues)

### Badges

* ![early crash](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/earlycrash.png)
    * `![early crash](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/earlycrash.png)`
    * Crashes early; the game isn't playable at all.
* ![heavy bugs](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/heavybugs.png)
    * `![heavy bugs](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/heavybugs.png)`
    * Has some heavy bugs, f.e. missing environment textures or game crashes after certain point.
* ![playable with minor bugs](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/minorbugs.png)
    * `![playable with minor bugs](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/minorbugs.png)`
    * Has some minor bugs that hinder "perfect" gameplay, f.e. flickering textures. The game should be finished / the main game functionality should work.
* ![playable with no bugs](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/nobugs.png)
    * `![playable with no bugs](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/nobugs.png)`
    * Has virtually no bugs. The game is "perfectly" playable, but still requires some manual tweaks, dependency replacements or similar.
* ![perfectly playable](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/perfect.png)
    * `![perfectly playable](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/perfect.png)`
    * Has virtually no bugs. The game is "perfectly" playable and only requires XnaToFna. Passing arguments to XnaToFna is okay if required. 

### Template

```
### Game: Some Game

**URL:** URL to the Steam Store or similar.

**[Optional] Patch URL:** URL to patch repository or similar.

![playable with minor bugs](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/minorbugs.png)

**[Optional] XnaToFna arguments:** `--anycpu`

**Description:** This game is almost perfectly playable. Unfortunately it suffers from a minor glitch when enabling fullscreen mode and not restarting.

**Changes required:**

* Rename `content` directory to `Content` (case sensitivity fix)
* Compile the provided `NativeCrap.dll` stub source. On Linux, `LD_PRELOAD` it. URL to the source.
    * Alternatively, patch the P/Invokes in `BindingCrap.dll`.

**[Optional] Currently blocking progress:**

* `Steam.dll` (mixed-mode dependency)

**Screenshots:**

* URL to screenshot 1
* URL to screenshot 2
```

### Example:

### Game: Some Game

**URL:** URL to the Steam Store or similar.

**[Optional] Patch URL:** URL to patch repository or similar.

![playable with minor bugs](https://raw.githubusercontent.com/0x0ade/XnaToFna-Tracker/master/badges/minorbugs.png)

**[Optional] XnaToFna arguments:** `--anycpu`

**Description:** This game is almost perfectly playable. Unfortunately it suffers from a minor glitch when enabling fullscreen mode and not restarting.

**Changes required:**

* Rename `content` directory to `Content` (case sensitivity fix)
* Compile the provided `NativeCrap.dll` stub source. On Linux, `LD_PRELOAD` it. URL to the source.
    * Alternatively, patch the P/Invokes in `BindingCrap.dll`.

**[Optional] Currently blocking progress:**

* `Steam.dll` (mixed-mode dependency)

**Screenshots:**

* URL to screenshot 1
* URL to screenshot 2
