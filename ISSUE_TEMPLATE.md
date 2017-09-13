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
