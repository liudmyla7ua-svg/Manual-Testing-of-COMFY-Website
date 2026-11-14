# COMFY Website — API Testing Checklist

**Project:** Manual Testing of COMFY Website  
**Testing Type:** API Testing  
**Tool:** Postman, Chrome DevTools  
**Priority:** High / Medium  
**Status:** Not Run

## 1. Product Search API

| ID | Test Scenario | Expected Result | Priority | Status |
|---|---|---|---|---|
| API-001 | Verify product search API with a valid search query | The API returns a list of products matching the search query | High | Passed |
| API-002 | Verify product search API with an empty search query | The API handles an empty search query correctly without an unexpected error | Medium | Passed |
| API-003 | Verify product search API with a non-existing product name | The API returns an empty result or an appropriate response indicating that no products were found | Medium | Passed |

## 2. Product Details API

| ID | Test Scenario | Expected Result | Priority | Status |
|---|---|---|---|---|
| API-004 | Verify product details API | The API returns correct information about the selected product | High | Passed |
| API-005 | Verify product price in API response | The API returns a valid product price that matches the product page | High | Passed |
| API-006 | Verify product availability information | The API returns correct product availability information | High | Passed |

## 3. Product Catalog API

| ID | Test Scenario | Expected Result | Priority | Status |
|---|---|---|---|---|
| API-007 | Verify product catalog API | The API returns a list of catalog categories with their IDs, names, paths, and nested subcategories | High | Passed |

## 4. Favorites API

| ID | Test Scenario | Expected Result | Priority | Status |
|---|---|---|---|---|
| API-008 | Verify favorites API | The API successfully returns the authenticated user's wishlist, including wishlist names, product IDs, and SKU values. | Medium | Passed |

## 5. Viewed Products API

| ID | Test Scenario | Expected Result | Priority | Status |
|---|---|---|---|---|
| API-009 | Verify viewed products API | The API returns the products recently viewed by the authenticated user | Medium | Not Run |

## 6. Authenticated User Account API

| ID | Test Scenario | Expected Result | Priority | Status |
|---|---|---|---|---|
| API-010 | Verify authenticated user account API | The API returns the correct account information for the authenticated user and does not expose unauthorized personal data | Medium | Not Run |

---

## General API Checks

For each discovered API request, verify:

- [ ] Correct HTTP method (GET, POST, PUT, PATCH, DELETE).
- [ ] Correct request URL.
- [ ] Correct HTTP status code.
- [ ] Response body contains expected data.
- [ ] Response format is valid (JSON, if applicable).
- [ ] Response headers are correct.
- [ ] Response time is reasonable.
- [ ] No unexpected error messages are returned.

## Test Environment

| Parameter | Value |
|---|---|
| Website | https://comfy.ua/ |
| API Testing Tool | Postman |
| Browser | Google Chrome |
| Developer Tools | Chrome DevTools |
| Test Type | Manual API Testing |

## Notes

- Actual API endpoints and HTTP methods will be identified through Chrome DevTools Network.
- Expected results should be confirmed against the actual website behavior and available requirements.
- Tests requiring authentication should be performed only with the tester's own account.
- No real customer data, passwords, access tokens, or session cookies should be included in public GitHub files.
- API requests that modify data should be tested only when their behavior and impact are understood.
