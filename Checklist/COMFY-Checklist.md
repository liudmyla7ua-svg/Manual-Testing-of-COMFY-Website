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
| CH-002 | Verify website logo | Clicking the logo redirects the user to the homepage |  Passed |
| CH-003 | Verify header navigation links | Each navigation link redirects the user to the correct page or section | Passed |
| CH-004 | Navigate to a product category | The correct product category page opens | Passed |
| CH-005 | Verify city selection | The list of available cities is displayed, and the selected city is shown correctly | Not Run |
| CH-006 | Verify language switching | Website content is displayed in the selected language, if language switching is available | Passed |
| CH-007 | Verify promotional banners | Clicking a promotional banner redirects the user to the corresponding promotion or page | Passed |
| CH-008 | Verify closing the sign-in pop-up | The pop-up closes, and the main page content remains accessible | Passed |
| CH-009 | Verify the customer support chat widget | The chat widget opens, and its main elements are available | Passed |
| CH-010 | Verify footer navigation links | Each footer link redirects the user to the corresponding page | Passed |
| CH-011 | Verify the Back to Top button | Clicking the button scrolls the page back to the top | Not Run |
| CH-012 | Verify delivery, warranty, payment, and return information links | The corresponding information pages or sections open successfully | Not Run |
| CH-013 | Verify social media links | Each social media link redirects the user to the corresponding platform |  ? |
| CH-014 | Verify App Store and Google Play links | The links redirect the user to the corresponding application pages | Passed |

## 2. Product Search

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-015 | Search for an existing product by its full name | Relevant products are displayed in the search results | Not Run |
| CH-016 | Search using a partial product name | Relevant search suggestions or results are displayed | Not Run |
| CH-017 | Search for a non-existing product | An appropriate no-results message is displayed | Not Run |
| CH-018 | Submit an empty search field | Search is not performed, or the website displays appropriate behavior | Not Run |
| CH-019 | Verify search suggestions | Suggestions correspond to the entered search query | Not Run |
| CH-020 | Search using special characters | The website handles special characters without errors or unexpected behavior | Not Run |

## 3. Product Catalog, Filters and Sorting

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-021 | Open a product category | Products are displayed correctly on the category page | Not Run |
| CH-022 | Apply an available product filter | Only products matching the selected filter are displayed | Not Run |
| CH-023 | Apply multiple product filters | Displayed products match all selected filter criteria | Not Run |
| CH-024 | Clear selected filters | The selected filters are removed, and the product list is updated | Not Run |
| CH-025 | Sort products by price ascending | Products are sorted from the lowest to the highest price | Not Run |
| CH-026 | Sort products by price descending | Products are sorted from the highest to the lowest price | Not Run |
| CH-027 | Navigate through product listing pages or load more products | The next products are loaded or the next page opens correctly | Not Run |

## 4. Product Cards on Homepage

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-028 | Verify product card information | Product cards display the product name, image, and current price | Not Run |
| CH-029 | Verify discounted product information | Discounted products display the original price, discount amount, and current price correctly | Not Run |
| CH-030 | Verify product ratings and review counts | Rating and review information is displayed correctly when available | Not Run |
| CH-031 | Click a product card | The corresponding product details page opens | Not Run |
| CH-032 | Add a product to Favorites from its card | The product is added to Favorites, or the user is prompted to log in | Not Run |
| CH-033 | Add a product to Compare from its card | The product is added to the comparison list | Not Run |

## 5. Product Details Page

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-034 | Open a product details page | The correct product details page opens | Not Run |
| CH-035 | Verify product name and price | The product name and current price are displayed correctly | Not Run |
| CH-036 | Verify product images | Product images load successfully and correspond to the selected product | Not Run |
| CH-037 | Verify product availability information | Product availability information is displayed correctly | Not Run |
| CH-038 | Verify product specifications | Product characteristics and specifications are displayed correctly | Not Run |
| CH-039 | Navigate through the product image gallery | The user can switch between product images successfully | Not Run |
| CH-040 | Verify product reviews section | Available customer reviews and ratings are displayed correctly | Not Run |

## 6. Shopping Cart

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-041 | Add a product to the cart | The selected product is successfully added to the shopping cart | Not Run |
| CH-042 | Add the same product to the cart again | The product quantity or cart contents are updated according to the website behavior | Not Run |
| CH-043 | Increase product quantity | The product quantity and total price are updated correctly | Not Run |
| CH-044 | Decrease product quantity | The product quantity and total price are updated correctly | Not Run |
| CH-045 | Remove a product from the cart | The selected product is removed successfully | Not Run |
| CH-046 | Open an empty shopping cart | An appropriate empty-cart message or state is displayed | Not Run |
| CH-047 | Refresh the page after adding a product to the cart | The cart contents remain consistent after refreshing the page | Not Run |
| CH-048 | Verify the cart total price | The total price is calculated correctly based on product prices and quantities | Not Run |

## 7. Checkout Process

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-049 | Proceed to checkout with a product in the cart | The checkout page or next checkout step opens successfully | Not Run |
| CH-050 | Submit the checkout form with empty required fields | Validation messages are displayed for required fields | Not Run |
| CH-051 | Enter an invalid phone number | The website prevents invalid input or displays an appropriate validation message | Not Run |
| CH-052 | Enter an invalid email format, if email is required | An appropriate validation message is displayed | Not Run |
| CH-053 | Verify available delivery options | Available delivery options are displayed correctly | Not Run |
| CH-054 | Verify available payment options | Available payment options are displayed correctly | Not Run |
| CH-055 | Verify the order total before placing an order | The order total corresponds to the selected products, quantities, and applicable delivery costs | Not Run |

## 8. Newsletter Subscription

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-056 | Submit the newsletter subscription form with a valid email address | The subscription is processed, and an appropriate confirmation message is displayed | Not Run |
| CH-057 | Submit the newsletter subscription form with an invalid email address | The website rejects the invalid email address and displays a validation message | Not Run |
| CH-058 | Submit the newsletter subscription form with an empty email field | The website prevents submission or displays an appropriate validation message | Not Run |

## 9. Promotional Sections and Product Carousels

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-059 | Navigate through a product carousel using the arrow buttons | The carousel displays the next or previous products correctly | Not Run |
| CH-060 | Click the "Show More" button in a product section | Additional products are displayed or the relevant product listing page opens | Not Run |
| CH-061 | Verify promotional product links | Clicking a promotional product or offer opens the corresponding product or promotion page | Not Run |

## 10. UI and Responsive Testing

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-062 | Verify homepage layout at desktop resolution (1440px) | All elements are displayed correctly without unintended overlap | Not Run |
| CH-063 | Verify homepage layout at tablet resolution (768px) | Content adapts to the viewport without unintended overlap or horizontal overflow | Not Run |
| CH-064 | Verify homepage layout at mobile resolution (375px) | Main content and interactive elements are displayed correctly without horizontal overflow | Not Run |
| CH-065 | Verify homepage layout at mobile resolution (320px) | Content remains accessible, readable, and usable on a small screen | Not Run |
| CH-066 | Verify product details page layout at tablet and mobile resolutions | Product information and interactive elements adapt correctly to smaller screens | Not Run |

---

## Test Execution Notes

- **Pass:** Actual result matches the expected result.
- **Fail:** Actual result does not match the expected result.
- **Blocked:** Test cannot be executed because of an external limitation.
- **Not Run:** Test has not been executed yet.

**Important:** All test results must be based on actual test execution. Any identified defects should be documented separately in the Bug Reports folder with supporting screenshots and reproduction steps.

**Note:** Some tests may depend on website functionality, user authorization, or available test data. If a feature is unavailable, record the reason rather than assuming that the test has passed.
No real orders or payments will be completed during testing.
