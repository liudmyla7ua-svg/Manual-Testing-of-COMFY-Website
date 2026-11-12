# COMFY Website — Test Checklist

**Project:** COMFY E-commerce Website  
**Website:** [https://comfy.ua/](https://comfy.ua/)  
**Testing Type:** Manual Testing  
**Environment:** Google Chrome / Windows 11 Pro 

**Test Status:** In Progress

---

## 1. Header Testing

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-001 | Verify website logo | Clicking the logo redirects the user to the homepage | Passed |
| CH-002 | Verify city selection | The list of available cities is displayed, and the selected city is shown correctly | Failed |
| CH-003 | Verify language switching | Website content is displayed in the selected language, if language switching is available | Passed |
| CH-004 | Verify the Catalog button | Clicking the Catalog button opens the categories menu | Passed |
| CH-005 | Verify Catalog menu display | All categories and subcategories are accessible, with no content clipping or overlapping | Failed |
| CH-006 | Verify header navigation links | Each header navigation link redirects the user to the correct page or section | Passed |
| CH-007 | Verify the Sign In button | Clicking the Sign In button opens the authorization pop-up | Passed |
| CH-008 | Verify the Compare button | Clicking the Compare button opens the comparison page or displays the appropriate empty state | Passed |
| CH-009 | Verify the Favorites button | Clicking the Favorites button opens the favorites page or prompts the user to log in | Passed |
| CH-010 | Verify the Notifications button | Clicking the Notifications button opens the notifications section or displays the appropriate state | Passed |
| CH-011 | Verify the Shopping Cart button | Clicking the Shopping Cart button opens the cart page or displays the empty-cart state | Passed |
| CH-012 | Verify header layout on Desktop | Header elements are correctly aligned and displayed without overlapping | Passed |
| CH-013 | Verify header layout on Tablet | Header elements adapt correctly to tablet screen widths | Passed |
| CH-014 | Verify header layout on Mobile | Header elements are displayed correctly and remain accessible on mobile screens | Passed |
| CH-015 | Verify header after page refresh | Header elements remain correctly displayed after refreshing the page | Passed |

## 2. Registration Testing

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-016 | Verify access to the registration form | The registration form opens successfully, if registration is available | Passed |
| CH-017 | Submit the registration form with empty required fields | The website prevents submission and displays appropriate validation messages | Passed |
| CH-018 | Enter an invalid phone number during registration | The website rejects the invalid phone number and displays a validation message | Passed |
| CH-019 | Enter a phone number with an incorrect country code | The website displays an appropriate validation message | Not Run |
| CH-020 | Register using a valid phone number | The website accepts the phone number and proceeds to the next registration step | Not Run |
| CH-021 | Verify registration using an already registered phone number | The website displays an appropriate message or handles the existing account according to the requirements | Not Run |
| CH-022 | Enter special characters in the name field | The website prevents submission and displays appropriate validation messages  | Not Run |
| CH-023 | Enter the name in Latin | The website prevents submission and displays appropriate validation messages | Not Run |
| CH-024 | Enter numbers in the name field | The website prevents submission and displays appropriate validation messages  | Not Run |
| CH-025 | Enter one Cyrillic letter in the name field | The website prevents submission and displays appropriate validation messages | Not Run |
| CH-026 | Enter the valid name in the name field | Registration is successful | Not Run |
| CH-027 | Verify registration form validation messages | Validation messages are clear, relevant, and displayed near the corresponding fields | Not Run |

## 3. Authorization Testing

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-023 | Open the authorization pop-up | The authorization pop-up opens successfully | Not Run |
| CH-024 | Close the authorization pop-up | The pop-up closes, and the homepage remains accessible | Passed |
| CH-025 | Submit the authorization form with an empty phone number | The website prevents submission and displays an appropriate validation message | Not Run |
| CH-026 | Enter an invalid phone number | The website rejects the invalid phone number and displays a validation message | Not Run |
| CH-027 | Enter a valid phone number | The website accepts the phone number and enables the next authorization step | Not Run |
| CH-028 | Enter an incorrect verification code | The website rejects the incorrect code and displays an appropriate error message | Not Run |
| CH-029 | Complete authorization with a valid verification code | The user is successfully authorized and the account information becomes available | Not Run |
| CH-030 | Verify authorization persistence after page refresh | The user remains authorized after refreshing the page | Not Run |
| CH-031 | Verify authorization through Google or Facebook | The user can proceed with social authorization, if this functionality is available | Not Run |
| CH-032 | Verify logout | The user is successfully logged out, and access to account-specific features requires authorization | Not Run |

## 4. Homepage and Navigation

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-033 | Open the homepage | Homepage loads successfully without critical errors | Passed |
| CH-034 | Navigate to a product category | The correct product category page opens | Passed |
| CH-035 | Verify promotional banners | Clicking a promotional banner redirects the user to the corresponding promotion or page | Passed |
| CH-036 | Verify the content of promotional banners | Promotional banner content is displayed correctly without visual defects | Failed |
| CH-037 | Verify the customer support chat widget | The chat widget opens, and its main elements are available | Passed |
| CH-038 | Verify the Back to Top button | Clicking the button scrolls the page back to the top | Passed |
| CH-039 | Verify delivery, warranty, payment, and return information links | The corresponding information pages or sections open successfully | Passed |
| CH-040 | Verify social media links | Each social media link redirects the user to the corresponding platform | Failed |
| CH-041 | Verify App Store and Google Play links | The links redirect the user to the corresponding application pages | Passed |

## 5. Product Search

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-042 | Search for an existing product by its full name | Relevant products are displayed in the search results | Passed |
| CH-043 | Search using a partial product name | Relevant search suggestions or results are displayed | Passed |
| CH-044 | Search by product brand and category | Search results display products matching the specified category and brand | Failed |
| CH-045 | Search for a non-existing product | An appropriate no-results message is displayed | Passed |
| CH-046 | Submit an empty search field | Search is not performed, or the website displays appropriate behavior | Passed |
| CH-047 | Verify search suggestions | Suggestions correspond to the entered search query | Passed |
| CH-048 | Search using special characters | The website handles special characters without errors or unexpected behavior | Passed |

## 6. Product Catalog, Filters and Sorting

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-049 | Open a product category | Products are displayed correctly on the category page | Passed |
| CH-050 | Apply an available product filter | Only products matching the selected filter are displayed | Passed |
| CH-051 | Apply multiple product filters | Displayed products match all selected filter criteria | Passed |
| CH-052 | Clear selected filters | The selected filters are removed, and the product list is updated | Passed |
| CH-053 | Sort products by price ascending | Products are sorted from the lowest to the highest price | Passed |
| CH-054 | Sort products by price descending | Products are sorted from the highest to the lowest price | Passed |
| CH-055 | Navigate through product listing pages or load more products | The next products are loaded or the next page opens correctly | Passed |

## 7. Product Cards on Homepage

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-056 | Verify product card information | Product cards display the product name, image, and current price | Passed |
| CH-057 | Verify discounted product information | Discounted products display the original price, discount amount, and current price correctly | Passed |
| CH-058 | Verify product ratings and review counts | Rating and review information is displayed correctly when available | Passed |
| CH-059 | Click a product card | The corresponding product details page opens | Passed |
| CH-060 | Add a product to Favorites from its card | The product is added to Favorites, or the user is prompted to log in | Passed |
| CH-061 | Add a product to Compare from its card | The product is added to the comparison list | Passed |

## 8. Product Details Page

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-062 | Open a product details page | The correct product details page opens | Passed |
| CH-063 | Verify product name and price | The product name and current price are displayed correctly | Passed |
| CH-064 | Verify product images | Product images load successfully and correspond to the selected product | Passed |
| CH-065 | Verify product availability information | Product availability information is displayed correctly | Passed |
| CH-066 | Verify product specifications | Product characteristics and specifications are displayed correctly | Passed |
| CH-067 | Navigate through the product image gallery | The user can switch between product images successfully | Passed |
| CH-068 | Verify product reviews section | Available customer reviews and ratings are displayed correctly | Passed |

## 9. Shopping Cart

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-069 | Add a product to the cart | The selected product is successfully added to the shopping cart | Passed |
| CH-070 | Add the same product to the cart again | The product quantity or cart contents are updated according to the website behavior | Passed |
| CH-071 | Increase product quantity | The product quantity and total price are updated correctly | Passed |
| CH-072 | Decrease product quantity | The product quantity and total price are updated correctly | Passed |
| CH-073 | Remove a product from the cart | The selected product is removed successfully | Passed |
| CH-074 | Open an empty shopping cart | An appropriate empty-cart message or state is displayed | Passed |
| CH-075 | Refresh the page after adding a product to the cart | The cart contents remain consistent after refreshing the page | Passed |
| CH-076 | Verify the cart total price | The total price is calculated correctly based on product prices and quantities | Passed |

## 10. Checkout Process

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-077 | Proceed to checkout with a product in the cart | The checkout page or next checkout step opens successfully | Passed |
| CH-078 | Submit the checkout form with empty required fields | Validation messages are displayed for required fields | Passed |
| CH-079 | Enter an invalid phone number | The website prevents invalid input or displays an appropriate validation message | Passed |
| CH-080 | Enter an invalid email format, if email is required | An appropriate validation message is displayed | Not Run |
| CH-081 | Verify available delivery options | Available delivery options are displayed correctly | Passed |
| CH-082 | Verify available payment options | Available payment options are displayed correctly | Passed |
| CH-083 | Verify the order total before placing an order | The order total corresponds to the selected products, quantities, and applicable delivery costs | Passed |

## 11. Newsletter Subscription

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-084 | Submit the newsletter subscription form with a valid email address | The subscription is processed, and an appropriate confirmation message is displayed | Passed |
| CH-085 | Submit the newsletter subscription form with an invalid email address | The website rejects the invalid email address and displays a validation message | Passed |
| CH-086 | Submit the newsletter subscription form with an empty email field | The website prevents submission or displays an appropriate validation message | Passed |

## 12. Promotional Sections and Product Carousels

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-087 | Navigate through a product carousel using the arrow buttons | The carousel displays the next or previous products correctly | Passed |
| CH-088 | Click the "Show More" button in a product section | Additional products are displayed or the relevant product listing page opens | Passed |
| CH-089 | Verify promotional product links | Clicking a promotional product or offer opens the corresponding product or promotion page | Not Run |

## 13. UI and Responsive Testing

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-090 | Verify homepage layout at desktop resolution (1440px) | All elements are displayed correctly without unintended overlap | Passed |
| CH-091 | Verify homepage layout at tablet resolution (768px) | Content adapts to the viewport without unintended overlap or horizontal overflow | Passed |
| CH-092 | Verify homepage layout at mobile resolution (375px) | Main content and interactive elements are displayed correctly without horizontal overflow | Passed |
| CH-093 | Verify homepage layout at mobile resolution (320px) | Content remains accessible, readable, and usable on a small screen | Passed |
| CH-094 | Verify product details page layout at tablet and mobile resolutions | Product information and interactive elements adapt correctly to smaller screens | Not Run |

## 14. Footer Testing

| **ID** | **Test Scenario** | **Expected Result** | **Status** |
|---|---|---|---|
| CH-095 | Verify footer visibility | The footer is displayed correctly at the bottom of the page | Not Run |
| CH-096 | Verify footer section headings | All footer section headings are visible and correctly displayed | Not Run |
| CH-097 | Verify footer navigation links | Each footer link redirects the user to the corresponding page | Passed |
| CH-098 | Verify the Press Center link | Clicking the "Прес-центр" link opens the Press Center page | Passed |
| CH-099 | Verify the Contact Us link | Clicking the contact link opens the corresponding contact information page | Not Run |
| CH-100 | Verify the Delivery link | Clicking the delivery link opens the delivery information page | Not Run |
| CH-101 | Verify the Returns link | Clicking the returns link opens the returns policy page | Not Run |
| CH-102 | Verify the Warranty link | Clicking the warranty link opens the warranty information page | Not Run |
| CH-103 | Verify customer support phone numbers | Phone numbers are visible and clickable | Not Run |
| CH-104 | Verify customer support email | Clicking the email address opens the default email application with the correct recipient | Not Run |
| CH-105 | Verify social media links | Each social media icon redirects to the corresponding platform | Not Run |
| CH-106 | Verify footer newsletter subscription form | The email field and subscription button are displayed and functional | Not Run |
| CH-107 | Verify newsletter form validation | Invalid email addresses are rejected, and appropriate validation messages are displayed | Not Run |
| CH-108 | Verify footer layout on Desktop | Footer elements are correctly aligned and do not overlap | Not Run |
| CH-109 | Verify footer layout on Tablet | Footer elements are displayed correctly at tablet screen widths | Not Run |
| CH-110 | Verify footer layout on Mobile | Footer elements are displayed correctly at mobile screen widths | Not Run |
| CH-111 | Verify footer text alignment and spacing | Text elements have appropriate margins, padding, and spacing | Not Run |
| CH-112 | Verify footer links hover state | Footer links display the correct hover effect when the cursor is moved over them | Not Run |
| CH-113 | Verify footer content after page refresh | Footer content remains correctly displayed after refreshing the page | Not Run |

---

## Test Execution Notes

- **Pass:** Actual result matches the expected result.
- **Fail:** Actual result does not match the expected result.
- **Blocked:** Test cannot be executed because of an external limitation.
- **Not Run:** Test has not been executed yet.

**Important:** All test results must be based on actual test execution. Any identified defects should be documented separately in the Bug Reports folder with supporting screenshots and reproduction steps.

**Note:** Some tests may depend on website functionality, user authorization, or available test data. If a feature is unavailable, record the reason rather than assuming that the test has passed. No real orders or payments will be completed during testing.
