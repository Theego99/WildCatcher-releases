# WildCatcher — Releases / リリース配布

This repository is the **update channel** for WildCatcher. It contains only the
update manifest (`version.json`) and the released Windows builds. No source code.

WildCatcher checks `version.json` on startup (at most once per day) and from
**About → Check for updates**. From version 2.1.3 onward the app downloads and
installs updates by itself — no manual download, no reinstall.

このリポジトリは WildCatcher の**アップデート配信用**です。更新情報
（`version.json`）と Windows 版のビルドのみを置いています。ソースコードは
含まれません。

WildCatcher はバージョン 2.1.3 以降、アプリ内で更新のダウンロードと
インストールを自動で行います。手動でのダウンロードや再インストールは不要です。

---

## Manual download / 手動ダウンロード

See [Releases](../../releases/latest) → `WildCatcher-Windows-x64.zip`.

1. Download and extract the archive
2. Open the `WildCatcher` folder
3. Run `WildCatcher.exe`

## `version.json`

```jsonc
{
  "version": "2.1.3",          // plain semver; compared against the running app
  "tag": "v2.1.3",
  "notes": "...",              // shown in the update dialog
  "page": "https://github.com/Theego99/WildCatcher-releases/releases/latest",
  "windows": {
    "url": "https://github.com/.../WildCatcher-Windows-x64.zip",
    "sha256": "...",           // verified after download; a mismatch aborts
    "size": 0                  // bytes, for the progress bar
  }
}
```
