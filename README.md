# NAA Checker Brief: live content

The NAA Checker Brief app downloads `content.json` from this repository each time it opens. It updates when the file's `contentVersion` is newer than its own copy.

To publish an update, replace `content.json` on the `main` branch with the new file. Raise `contentVersion` first.

App source: private repository `naa-checker--brief`.
