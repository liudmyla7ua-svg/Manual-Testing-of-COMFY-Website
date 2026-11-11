# BUG-003 — Viber Social Media Link Opens a Blank Page

**Title:** Viber social media link opens a blank browser page instead of redirecting the user to Viber.

**Environment:**
- Website: https://comfy.ua/ua/
- Browser: Google Chrome
- Operating System: Windows 11
- Browser mode: Incognito

**Preconditions:**
- The user opens the COMFY website.
- The Viber social media link is available on the page.

**Steps to Reproduce:**
1. Open https://comfy.ua/ua/.
2. Scroll to the section containing social media links.
3. Click the Viber icon.
4. Observe the browser behavior.

**Actual Result:**
The browser opens a blank page with the following URL:

`viber://pa?chatURI=comfy.ua`

The user is not redirected to the expected Viber page or community.

**Expected Result:**
Clicking the Viber social media link should open the corresponding Viber page or community. If the Viber application is not installed, the user should receive an appropriate alternative or a clear message.

**Severity:** Medium (provisional)

**Priority:** Medium (provisional)

**Attachment:** Screenshot showing the blank browser page after clicking the Viber link.
