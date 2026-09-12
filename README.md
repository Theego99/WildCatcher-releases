# WildCatcher — Releases / リリース配布

## アップデート

**2.2.0 以降をお使いの方:** アプリ内の「更新」または「About → 更新の確認」から更新できます。ライセンス、モデル、設定プロファイルを保持します。

**2.1.3 以前をお使いの方:** 旧バージョンの更新確認に不具合があるため、現在のセットアップを一度実行してください。以後はアプリ内で更新できます。

## 初めてインストールする場合 / First installation

| パソコン / Computer | ダウンロード / Download |
|---|---|
| Windows 64-bit | [最新版のリリース](../../releases/latest) にある `_Setup.exe` を実行してください。 |
| Mac — Apple Silicon (M1/M2/M3/M4 など) | [Mac Apple Silicon DMG](../../releases/latest/download/WildCatcher-macOS-arm64.dmg) |
| Mac — Intel | [Mac Intel DMG](../../releases/latest/download/WildCatcher-macOS-x64.dmg) |

Mac: DMG を開き、WildCatcher を Applications にドラッグしてください。動画再生に別途 VLC は不要です。現在の Mac ビルドは Developer ID 署名・公証が未設定のため、初回起動時に macOS の承認が必要になる場合があります。

GUI、CLI、アップデーターを同梱しています。アプリ内更新用の ZIP も Assets にあります。

## Source code links / ソースコードのリンクについて

この公開リポジトリには配布情報と `version.json` のみを置いています。アプリケーションのソースコードは公開していません。GitHub の「Source code」リンクに含まれるのは、このリポジトリの説明と更新情報だけです。

This public repository contains release information and update metadata only. The application source is private. GitHub's automatic **Source code** archives contain this repository's README and version information, not WildCatcher's application source.

Windows clients on 2.2.0 or later can update inside the app. Mac packages support subsequent in-app updates, with user data stored outside the application bundle. The current Mac builds are ad-hoc signed; warning-free first launch requires Developer ID signing and notarization.

## 更新が途中で止まった場合 / Update recovery

旧バージョンで更新時にアプリが閉じたまま戻らない場合は、最新版の `_Setup.exe` を一度実行してください。アプリとスタートメニューのショートカットを修復します。ライセンス・モデル・プロファイルは保持されます。

If an older Windows app closes during an update and does not reopen, run the current `_Setup.exe` once. This repairs the installed app and Start-menu shortcut while keeping licences, models and profiles. The old helper cannot be fixed by another archive download alone.
