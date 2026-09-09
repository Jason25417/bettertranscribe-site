# Scritto 言录 — Support & Privacy

Public support and privacy pages for the **Scritto 言录** app (App Store), previously named
BetterTranscribe — the bundle identifier is still `com.jason.BetterTranscribe`.
Contains only static text, no source code.

- `index.html` — support / FAQ (`support_url` in App Store Connect)
- `privacy.html` — privacy policy (`privacy_policy_url` in App Store Connect)

The in-app entries are Settings → General → About → "Support & Feedback" / "Privacy Policy"
(and, on macOS, the Help menu). Change a URL here and you must change it in
`BetterTranscribe/Models/Changelog.swift` and in the ASC metadata too.
