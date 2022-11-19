# Subtitle Composer (org.kde.subtitlecomposer)

[Homepage](https://subtitlecomposer.kde.org/) |
[Matrix Chat](https://webchat.kde.org/#/room/#subtitlecomposer:kde.org) |
[Sources](https://invent.kde.org/multimedia/subtitlecomposer)

## Reporting bugs

**Before filling a bug, please test if the bug is reproduceable with the
classic non-Flatpak version of this application.**

- If the bug is only reproducible with the **Flatpak version** of this
  application, please file an [Issue here][issue].

- If the bug is also reproducible with the **non-Flatpak version** of this
  application, please take a look at the [currently opened bugs][bugs] and if
  it has not been reported yet, file a bug at
  [bugs.kde.org](https://bugs.kde.org).

**If you have any doubt, please file an [Issue here][issue].**

## Permissions rationale

This application requests the following restricted permissions:

- `--filesystem=host`
  - required to automatically open video file - open/search videos in subtitle directory
  - required to open bitmap subtitles sparsed through several files (e.g. VobSub .idx/.sub)
  - required to open media streams spanning several files (e.g. DVD/VOB)
  - required to save symbol cache files (.sym) after OCR next to bitmap subtitles

[issue]: https://github.com/flathub/org.kde.subtitlecomposer/issues/new
[bugs]: https://bugs.kde.org/buglist.cgi?bug_status=UNCONFIRMED&bug_status=CONFIRMED&bug_status=ASSIGNED&bug_status=REOPENED&product=subtitlecomposer&query_format=advanced
