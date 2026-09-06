# matchcut-legal

The privacy policy, terms of use and support pages for **MatchCut**, served by
GitHub Pages and linked from the App Store and Play Store listings and from
inside the app (Settings and the paywall).

- Privacy Policy — <https://hamzacakmakk.github.io/matchcut-legal/privacy.html>
- Terms of Use — <https://hamzacakmakk.github.io/matchcut-legal/terms.html>
- Support — <https://hamzacakmakk.github.io/matchcut-legal/support.html>

Plain static HTML, no build step: edit a file, push to `main`, and Pages
republishes within a minute.

The in-app links live in `src/lib/legal.ts`. Note that the paywall's "Terms"
link points at Apple's standard EULA rather than `terms.html`, because that is
the licence the app ships under in App Store Connect.
