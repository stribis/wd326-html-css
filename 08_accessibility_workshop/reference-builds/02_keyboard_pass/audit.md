# Artist Website Keyboard Audit - Example

| Location | Issue | Who is affected | Repair | Retest result |
| --- | --- | --- | --- | --- |
| Whole page | CSS removed every focus outline | Keyboard and switch users | Add a high-contrast `:focus-visible` outline | Focus is visible on every control |
| Hero | A focusable `div` looked actionable but could not activate | Keyboard, voice, and assistive-technology users | Replace with a real link to the release | Enter follows the link |
| Before navigation | No way to bypass repeated links | Keyboard and screen-reader users | Add a skip link targeting `main` | First Tab reveals the skip link |
