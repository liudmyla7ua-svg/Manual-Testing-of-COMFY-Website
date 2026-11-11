# COMFY Website — Test Checklist

**Project:** COMFY E-commerce Website  
**Website:** https://comfy.ua/  
**Testing Type:** Manual Testing  
**Environment:** Google Chrome / Windows  
**Test Status:** In Progress

---

## 1. Homepage and Navigation

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-001 | Open the homepage | Homepage loads successfully without critical errors | Passed |
| CH-002 | Verify website logo | Clicking the logo redirects the user to the homepage | Passed |
| CH-003 | Verify city selection | The list of available cities is displayed, and the selected city is shown correctly | Failed |
| CH-004 | Verify the Catalog button | Clicking on the Catalog button opens the page with categories list | Passed |
| CH-005 | Verify Catalog menu display | 	The Catalog menu is displayed correctly. All categories and subcategories are accessible, with no content clipping or overlapping | Failed |
| CH-006 | Verify header navigation links | Each navigation link redirects the user to the correct page or section | Passed |
| CH-007 | Navigate to a product category | The correct product category page opens | Passed |
| CH-008 | Verify language switching | Website content is displayed in the selected language, if language switching is available | Passed |
| CH-009 | Verify promotional banners | Clicking a promotional banner redirects the user to the corresponding promotion or page | Passed |
| CH-010 | Verify closing the sign-in pop-up | The pop-up closes, and the main page content remains accessible | Passed |
| CH-011 | Verify the customer support chat widget | The chat widget opens, and its main elements are available | Passed |
| CH-012 | Verify footer navigation links | Each footer link redirects the user to the corresponding page | Passed |
| CH-013 | Verify the Back to Top button | Clicking the button scrolls the page back to the top | Passed |
| CH-014 | Verify delivery, warranty, payment, and return information links | The corresponding information pages or sections open successfully | Passed |
| CH-015 | Verify social media links | Each social media link redirects the user to the corresponding platform |  ? |
| CH-016 | Verify App Store and Google Play links | The links redirect the user to the corresponding application pages | Passed |

## 2. Product Search

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-017 | Search for an existing product by its full name | Relevant products are displayed in the search results | Passed |
| CH-018 | Search using a partial product name | Relevant search suggestions or results are displayed | ? |
| CH-019 | Search for a non-existing product | An appropriate no-results message is displayed | Passed |
| CH-020 | Submit an empty search field | Search is not performed, or the website displays appropriate behavior | Passed |
| CH-021 | Verify search suggestions | Suggestions correspond to the entered search query | Passed |
| CH-022 | Search using special characters | The website handles special characters without errors or unexpected behavior | Passed |

## 3. Product Catalog, Filters and Sorting

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-023 | Open a product category | Products are displayed correctly on the category page | Passed |
| CH-024 | Apply an available product filter | Only products matching the selected filter are displayed | Passed |
| CH-025 | Apply multiple product filters | Displayed products match all selected filter criteria | Passed |
| CH-026 | Clear selected filters | The selected filters are removed, and the product list is updated | Passed |
| CH-027 | Sort products by price ascending | Products are sorted from the lowest to the highest price | Passed |
| CH-028 | Sort products by price descending | Products are sorted from the highest to the lowest price | Passed |
| CH-029 | Navigate through product listing pages or load more products | The next products are loaded or the next page opens correctly | Passed |

## 4. Product Cards on Homepage

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-030 | Verify product card information | Product cards display the product name, image, and current price | Passed |
| CH-031 | Verify discounted product information | Discounted products display the original price, discount amount, and current price correctly | Passed |
| CH-032 | Verify product ratings and review counts | Rating and review information is displayed correctly when available | Passed |
| CH-033 | Click a product card | The corresponding product details page opens | Passed |
| CH-034 | Add a product to Favorites from its card | The product is added to Favorites, or the user is prompted to log in | Passed |
| CH-035 | Add a product to Compare from its card | The product is added to the comparison list | Passed |

## 5. Product Details Page

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-036 | Open a product details page | The correct product details page opens | Passed |
| CH-037 | Verify product name and price | The product name and current price are displayed correctly | Passed |
| CH-038 | Verify product images | Product images load successfully and correspond to the selected product | Passed |
| CH-039 | Verify product availability information | Product availability information is displayed correctly | Passed |
| CH-040 | Verify product specifications | Product characteristics and specifications are displayed correctly | Passed |
| CH-041 | Navigate through the product image gallery | The user can switch between product images successfully | Passed |
| CH-042 | Verify product reviews section | Available customer reviews and ratings are displayed correctly | Passed |

## 6. Shopping Cart

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-043 | Add a product to the cart | The selected product is successfully added to the shopping cart | Passed |
| CH-044 | Add the same product to the cart again | The product quantity or cart contents are updated according to the website behavior | Passed |
| CH-045 | Increase product quantity | The product quantity and total price are updated correctly | Passed |
| CH-046 | Decrease product quantity | The product quantity and total price are updated correctly | Passed |
| CH-047 | Remove a product from the cart | The selected product is removed successfully | Passed |
| CH-048 | Open an empty shopping cart | An appropriate empty-cart message or state is displayed | Passed |
| CH-049 | Refresh the page after adding a product to the cart | The cart contents remain consistent after refreshing the page | Passed |
| CH-050 | Verify the cart total price | The total price is calculated correctly based on product prices and quantities | Passed |

## 7. Checkout Process

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-051 | Proceed to checkout with a product in the cart | The checkout page or next checkout step opens successfully | Passed |
| CH-052 | Submit the checkout form with empty required fields | Validation messages are displayed for required fields | Passed |
| CH-053 | Enter an invalid phone number | The website prevents invalid input or displays an appropriate validation message | Passed |
| CH-054 | Enter an invalid email format, if email is required | An appropriate validation message is displayed | ? |
| CH-055 | Verify available delivery options | Available delivery options are displayed correctly | Passed |
| CH-056 | Verify available payment options | Available payment options are displayed correctly | Passed |
| CH-057 | Verify the order total before placing an order | The order total corresponds to the selected products, quantities, and applicable delivery costs | Passed |

## 8. Newsletter Subscription

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-058 | Submit the newsletter subscription form with a valid email address | The subscription is processed, and an appropriate confirmation message is displayed | Passed |
| CH-059 | Submit the newsletter subscription form with an invalid email address | The website rejects the invalid email address and displays a validation message | Passed |
| CH-060 | Submit the newsletter subscription form with an empty email field | The website prevents submission or displays an appropriate validation message | Passed |

## 9. Promotional Sections and Product Carousels

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-061 | Navigate through a product carousel using the arrow buttons | The carousel displays the next or previous products correctly | Passed |
| CH-062 | Click the "Show More" button in a product section | Additional products are displayed or the relevant product listing page opens | Passed |
| CH-063 | Verify promotional product links | Clicking a promotional product or offer opens the corresponding product or promotion page | ? |

## 10. UI and Responsive Testing

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-064 | Verify homepage layout at desktop resolution (1440px) | All elements are displayed correctly without unintended overlap | Passed |
| CH-065 | Verify homepage layout at tablet resolution (768px) | Content adapts to the viewport without unintended overlap or horizontal overflow | Passed |
| CH-066 | Verify homepage layout at mobile resolution (375px) | Main content and interactive elements are displayed correctly without horizontal overflow | Passed |
| CH-067 | Verify homepage layout at mobile resolution (320px) | Content remains accessible, readable, and usable on a small screen | Passed |
| CH-068 | Verify product details page layout at tablet and mobile resolutions | Product information and interactive elements adapt correctly to smaller screens | ? |

---

## Test Execution Notes

- **Pass:** Actual result matches the expected result.
- **Fail:** Actual result does not match the expected result.
- **Blocked:** Test cannot be executed because of an external limitation.
- **Not Run:** Test has not been executed yet.

**Important:** All test results must be based on actual test execution. Any identified defects should be documented separately in the Bug Reports folder with supporting screenshots and reproduction steps.

**Note:** Some tests may depend on website functionality, user authorization, or available test data. If a feature is unavailable, record the reason rather than assuming that the test has passed.
No real orders or payments will be completed during testing.
