# Voice Dictation Extension — pages

Welcome, uninstall and feedback pages for the Voice Dictation Extension Chrome extension, served via GitHub Pages.

- `/welcome/` — opens once after installation
- `/uninstall/` — removal reasons form, opens when the extension is removed
- `/feedback/` — one-question form, opens from the rating prompt after 1 to 3 stars

The privacy policy is not here: it lives at https://pinwisp.com/voice-dictation-extension/privacy/.

Answers from the uninstall and feedback forms go to Google Forms (`FORM_ID` and entry constants in each page's script); with an empty `FORM_ID` the page sends nothing and only shows the thank-you state. The three pages count visits with Umami; the extension itself has no analytics.
