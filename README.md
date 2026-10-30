# Life Simple

Your money and to-do tracker for life's big moments — the Life Simple Tracker spreadsheet, as an Android app.

- 8 events: Wedding, Baby, First Home, Big Move, Graduation, Retirement, New Job, My Event (renamable)
- Each has Money In, a budget (Planned / Actual / Difference / Left over), a checklist and a tips box
- Everything is saved on the phone. No account, no internet needed.

## How builds work
Every push to `main` runs **Actions → Build Android app**, which produces:
- `LifeSimple-test-APK` — install directly on an Android phone to try it
- `LifeSimple-PlayStore-AAB` — upload to Google Play Console (signed when the `KEYSTORE_BASE64`, `KEYSTORE_PASSWORD` and `KEY_ALIAS` secrets are set)

The app itself is `www/index.html`. App ID: `com.lifesimple.tracker`.
