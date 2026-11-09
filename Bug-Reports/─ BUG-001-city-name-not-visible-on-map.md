# BUG-001: Selected City Name Is Not Displayed on the Map for Some Cities

**Severity:** Low  
**Priority:** Low  
**Component:** Homepage / Store Selection / Map  
**Environment:**
- Browser: Google Chrome
- OS: Windows
- Website: https://comfy.ua/

### Preconditions
The COMFY homepage is open.

### Steps to Reproduce
1. Open the COMFY homepage.
2. Open the store selection window.
3. Select "Mykolaiv" from the list of cities.
4. Check whether the selected city name is displayed on the map.
5. Repeat the same steps for "Ivano-Frankivsk".
6. Repeat the test for "Kyiv".

### Actual Result
When selecting Mykolaiv and Ivano-Frankivsk, the city names are not clearly displayed directly on the map.

When selecting Kyiv, the city name is clearly visible on the map.

### Expected Result
The map should provide a clear visual indication of the selected city. The map display should be consistent across different cities.

### Attachments
- Mykolaiv map screenshot
- Ivano-Frankivsk map screenshot
- Kyiv map screenshot (comparison)

- ## Attachments

### 1. Mykolaiv — city name is not displayed
![Mykolaiv map](Screenshots/01-mykolaiv-map.png)

### 2. Ivano-Frankivsk — city name is not displayed
![Ivano-Frankivsk map](Screenshots/02-ivano-frankivsk-map.png)

### 3. Kyiv — city name is displayed correctly
![Kyiv map](Screenshots/03-kyiv-map-reference.png)
