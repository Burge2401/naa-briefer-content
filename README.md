# NAA Checker Brief: live content

The NAA Checker Brief app downloads `content.json` from this repository each time it opens. It updates when the file's `contentVersion` is newer than its own copy.

To publish an update, replace `content.json` on the `main` branch with the new file. Raise `contentVersion` first.

App source: private repository `naa-checker--brief`.

## What is not stored here

Third-party authority documents (examiner handbooks, forms, briefings) are copyrighted by their authorities and are not published in this repository. The app quotes short verbatim passages with their source, version and retrieval date. The full documents and the register of official source links are kept privately by the app owner.
