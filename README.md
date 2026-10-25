# Grammar Quest — version 1.4

An offline-first Android grammar practice game designed for short daily sessions.

## Included in this version
- 60+ built-in grammar and workplace-English questions (the question bank is fixed in this app version).
- Immediate explanations and XP/level/accuracy tracking.
- Daily question goal and consecutive-day streak tracking.
- Incorrect answers are saved for review.
- A personal sentence notebook lets you save sentences on this device. The notebook does **not** automatically correct submitted sentences.
- Progress is stored locally in the app/WebView on the device; there is no account or cloud sync.

## Important content behavior
The built-in question bank does not automatically grow just because you use the app for more than 30 days. It cycles through its built-in questions and then repeats. New built-in lessons require an app update (or a future connected content service). You can keep adding your own sentences to the local notebook, but those entries are not automatically checked for grammar.

## Get an APK
This source project includes a GitHub Actions workflow that builds a debug APK. The APK has **not** been compiled or tested on a physical Android device as part of this package.

1. Create a GitHub repository and upload the **contents** of this project folder (so `settings.gradle` and `app/` are at the repository root).
2. Open the repository's **Actions** tab and run **Build Grammar Quest APK** (or push to `main`).
3. Open the successful workflow run and download the `grammar-quest-debug-apk` artifact. Extract it to get `app-debug.apk`.
4. Transfer the APK to your Android phone, allow installation from that source when prompted, and install it.

This is a debug build for personal testing, not a Play Store-signed release. Check the app on your phone before relying on it for daily learning.


## Version 1.3 roadmap update
- Added a 36-month learning roadmap screen.
- Added an extra-practice shortcut with no daily exercise cap.
- Important: the roadmap describes the intended three-year progression; the currently bundled exercise bank is still finite and will repeat. The full three-year unique content library is not yet included.
- Sentence free-text responses are self-checked against model answers; they are not automatically graded.
- APK build and physical-device tests have not yet been completed.


## Version 1.4 placement screening
- 16-question placement screening with four questions per skill: grammar, sentence making, daily-life vocabulary, and office English.
- Results are stored locally and show a provisional recommendation for each skill. The screening does not award XP or affect the learner's normal quiz accuracy.
- The screening is not an official CEFR assessment. Four questions per skill are only a first estimate.
- Critical limitation: the existing quiz bank is not fully tagged by skill/difficulty. Therefore, the saved plan is guidance; it does not yet automatically skip every mastered topic or adapt every subsequent question.
- APK compilation and physical-device testing remain outstanding.


## Version 1.4 build note

The Android app version is set to **1.4**. This ZIP contains source code and a GitHub Actions workflow; it is not itself an APK. A compiled APK can only be confirmed after the workflow completes successfully.
