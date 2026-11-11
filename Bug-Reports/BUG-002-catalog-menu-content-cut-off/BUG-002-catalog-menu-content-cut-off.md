# BUG-002: Catalog Menu Content Is Cut Off and Cannot Be Fully Viewed

**Severity:** Medium  
**Priority:** Medium  
**Component:** Homepage / Catalog Menu / Scrolling

### Environment
- Browser: Google Chrome
- Operating System: Windows
- Website: https://comfy.ua/ua/
- Browser zoom: 100%
- Browser window: Maximized
- DevTools: Closed

### Preconditions
1. Open the COMFY website.
2. Make sure the browser window is maximized and the zoom level is set to 100%.

### Steps to Reproduce
1. Open https://comfy.ua/ua/.
2. Click the **Catalog** button.
3. Scroll down through the catalog menu using the mouse wheel.
4. Continue scrolling until the menu cannot be scrolled any further.
5. Observe the bottom part of the catalog menu.

### Expected Result
The catalog menu should scroll correctly, allowing the user to view all categories and subcategories without any content being cut off or inaccessible.

### Actual Result
The catalog menu does not display all its content correctly. When scrolling down as far as possible, part of the bottom content remains cut off and cannot be fully viewed.

### Additional Information
- The issue persists when Chrome zoom is set to 100%.
- The browser window is maximized.
- The issue occurs when DevTools is closed.
- When DevTools is opened, the issue is not reproduced.

### Attachments
Screenshots demonstrating the issue are attached.
