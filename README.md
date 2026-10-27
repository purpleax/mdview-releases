# mdview

Downloads of **mdview**, a small native Mac app for reading and editing Markdown, HTML, JSON, plain text and code (including Fastly VCL), and PDFs.

**Latest: mdview 3.17.0** (27 October 2026). **Apple AI** joins Claude and GPT in Ask AI: Apple's on-device model, on a Mac with macOS 26.4 or later and Apple Intelligence on. It needs no key, costs nothing and sends nothing anywhere, and it is the provider until you save an API key or choose another. It reads the text you select, or a short document, and answers in text; **Insert** puts a rewrite in place of the selection. The Ask AI panel also gains an **Ask AI About Selection** button.

**[Download the latest version](https://github.com/purpleax/mdview-releases/releases/latest)**: open `mdview-3.17.0.dmg` and drag **mdview** onto **Applications**. It is signed and notarized by Apple, so it opens straight away.

Requires macOS 14 or later on an Apple Silicon Mac. Apple AI in Ask AI needs macOS 26.4 or later with Apple Intelligence turned on.

**[User manual](MANUAL.md)**: every feature, keyboard shortcuts, settings and troubleshooting. The same manual is in the app under **Help › mdview Manual**.

To update, choose **mdview › Check for Updates…** in the app. From 3.16.0, **Install and Relaunch** downloads the new version, checks it and installs it for you; earlier versions open the download in your browser. Your settings are kept.

## What's new

- **3.17.0** (27 October 2026): **Apple AI** joins Claude and GPT in Ask AI: Apple's on-device model, on a Mac with macOS 26.4 or later and Apple Intelligence on. It needs no key, costs nothing and sends nothing anywhere, and it is the provider until you save an API key or choose another. It reads the text you select, or a short document, and answers in text; **Insert** puts a rewrite in place of the selection. The Ask AI panel also gains an **Ask AI About Selection** button.
- **3.16.0** (19 October 2026): **Check for Updates** now installs the update for you: **Install and Relaunch** downloads the new version, checks that it's signed by mdview's developer and notarized by Apple, replaces mdview (the old version goes to the Trash) and opens it again. From the disk image or a folder mdview can't change, it still downloads the update in your browser.
- **3.15.0** (18 October 2026): **Find and Replace on the page**: replace text right in Visual mode and Split, for Markdown and HTML pages, with Match Case and Whole Words; Replace All is a single undo. HTML pages also get a find bar of their own.
- **3.14.2** (18 October 2026): More privacy and safety: documents never load anything over plain `http://`, and the new **Load remote images and content** setting (on by default) stops them loading anything from the web; Quick Look previews never do. A document can only show images and other files from its own folder or git repository, and Export as HTML includes only those. Large videos in HTML pages no longer pause the app while they load. Check for Updates only opens GitHub pages, and syntax checks ignore a script's `#!` line.
- **3.14.1** (17 October 2026): Safer links and pages: a link in a document to a file mdview doesn't open (an app, a script, an installer) now shows it in Finder instead of launching it, and an HTML page can no longer redirect itself to another site or show other sites or files in frames.

Older versions: each [release](https://github.com/purpleax/mdview-releases/releases) lists what's new in that version.
