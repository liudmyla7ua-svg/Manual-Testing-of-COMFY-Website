# BUG-004 — Search Results Do Not Match the Specified Brand

**Title:** Search results include products that do not match the specified brand

**Environment:**
- Website: https://comfy.ua/ua/
- Browser: Google Chrome
- Operating System: Windows
- Test type: Manual Testing

**Test Case ID:** CH-019 — Search by product brand and category

**Preconditions:**
- The COMFY website is opened.
- The user is on the homepage.

**Steps to Reproduce:**
1. Open the COMFY website.
2. Enter `ноутбук lenovo ThinkPad` into the search field.
3. Click the **Search** button.
4. Review the products displayed on the first results page.
5. Enter `телевізор samsung` into the search field.
6. Click the **Search** button.
7. Review the products displayed on the first results page.

**Expected Result:**
Search results should primarily display products matching the specified product category and brand or product series.

**Actual Result:**
- For the search query `ноутбук lenovo ThinkPad`, the first results include Lenovo IdeaPad and Lenovo LOQ laptops instead of ThinkPad laptops.
- For the search query `телевізор samsung`, the first results include Kivi TVs instead of Samsung TVs.

**Severity:** Medium (suggested; subject to confirmation)

**Priority:** Medium (suggested)

**Attachments:**
- `BUG-004-search-lenovo-thinkpad.png`
- `BUG-004-search-samsung-tv.png`

**Additional Notes:**
The search functionality appears to return products that match the general product category but do not necessarily match the specified brand or product series. Further verification against the search requirements is recommended.
