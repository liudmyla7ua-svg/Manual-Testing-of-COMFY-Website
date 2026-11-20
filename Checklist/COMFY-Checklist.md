# COMFY Website — Test Checklist

**Project:** COMFY E-commerce Website  
**Website:** https://comfy.ua/  
**Testing Type:** Manual Testing  
**Environment:** Google Chrome / Windows 11 Pro  

**Test Status:** In Progress

---

## 1. Header Testing

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| HDR-001 | Verify website logo | Clicking the logo redirects the user to the homepage | Passed |
| HDR-002 | Verify city selection | The list of available cities is displayed, and the selected city is shown correctly | Failed |
| HDR-003 | Verify language switching | Website content is displayed in the selected language, if language switching is available | Passed |
| HDR-004 | Verify the Catalog button | Clicking the Catalog button opens the categories menu | Passed |
| HDR-005 | Verify Catalog menu display | All categories and subcategories are accessible and displayed without clipping or overlapping | Failed |
| HDR-006 | Verify header navigation links | Each header navigation link redirects the user to the correct page or section | Passed |
| HDR-007 | Verify the Sign In button | Clicking the Sign In button opens the authorization pop-up | Passed |
| HDR-008 | Verify the Compare button | Clicking the Compare button opens the comparison page or displays the appropriate empty state | Passed |
| HDR-009 | Verify the Favorites button | Clicking the Favorites button opens the Favorites page or prompts the user to sign in | Passed |
| HDR-010 | Verify the Notifications button | Clicking the Notifications button opens the Notifications section or displays the appropriate state | Passed |
| HDR-011 | Verify the Shopping Cart button | Clicking the Shopping Cart button opens the cart page or displays the empty-cart state | Passed |
| HDR-012 | Verify header layout on Desktop | Header elements are correctly aligned and displayed without overlapping | Passed |
| HDR-013 | Verify header layout on Tablet | Header elements adapt correctly to tablet screen widths | Passed |
| HDR-014 | Verify header layout on Mobile | Header elements are displayed correctly and remain accessible on mobile screens | Passed |
| HDR-015 | Verify header after page refresh | Header elements remain correctly displayed after refreshing the page | Passed |

## 2. Registration Testing

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| REG-001 | Verify access to the registration form | The registration form opens successfully, if registration is available | Passed |
| REG-002 | Submit the registration form with empty required fields | The website prevents submission and displays appropriate validation messages | Passed |
| REG-003 | Enter an invalid phone number during registration | The website rejects the invalid phone number and displays a validation message | Passed |
| REG-004 | Enter a phone number with an incorrect country code | The website displays an appropriate validation message | Passed |
| REG-005 | Register using a valid phone number and select the SMS verification option | The website accepts the phone number and sends an SMS containing a verification code | Passed |
| REG-006 | Register using a valid phone number and select the phone call verification option | The website accepts the phone number, and the user receives an automated call with a verification code | Passed |
| REG-007 | Verify registration using an already registered phone number | The website displays an appropriate message or handles the existing account according to the requirements | Passed |
| REG-008 | Enter special characters in the name field | The website validates the entered characters according to the registration requirements | Passed |
| REG-009 | Enter a name using Latin characters | The website validates the entered name according to the registration requirements | Passed |
| REG-010 | Enter numbers in the name field | The website validates the entered numbers according to the registration requirements | Passed |
| REG-011 | Enter a single Cyrillic letter in the name field | The website validates the name length and displays an appropriate message if the input does not meet the requirements | Passed |
| REG-012 | Enter a valid name in the name field | The website accepts the valid name and allows the registration process to continue | Passed |
| REG-013 | Verify registration form validation messages | Validation messages are clear, relevant, and displayed near the corresponding fields | Passed |

## 3. Authorization Testing

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| AUTH-001 | Open the authorization pop-up | The authorization pop-up opens successfully | Passed |
| AUTH-002 | Close the authorization pop-up | The pop-up closes, and the homepage remains accessible | Passed |
| AUTH-003 | Submit the authorization form with an empty phone number | The website prevents submission and displays an appropriate validation message | Passed |
| AUTH-004 | Enter an invalid phone number | The website rejects the invalid phone number and displays a validation message | Passed |
| AUTH-005 | Enter a valid phone number | The website accepts the phone number and enables the next authorization step | Passed |
| AUTH-006 | Enter an incorrect verification code | The website rejects the incorrect code and displays an appropriate error message | Passed |
| AUTH-007 | Complete authorization with a valid verification code | The user is successfully authorized, and account information becomes available | Passed |
| AUTH-008 | Verify authorization persistence after page refresh | The user remains authorized after refreshing the page while the session is valid | Passed |
| AUTH-009 | Verify authorization through Google or Facebook | The user can proceed with social authorization, if this functionality is available | Passed |
| AUTH-010 | Verify logout | The user is successfully logged out, and access to account-specific features requires authorization | Passed |

## 4. Homepage and Navigation

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| HOME-001 | Open the homepage | The homepage loads successfully without critical errors | Passed |
| HOME-002 | Navigate to a product category | The correct product category page opens | Passed |
| HOME-003 | Verify promotional banners | Clicking a promotional banner redirects the user to the corresponding promotion or page | Passed |
| HOME-004 | Verify promotional banner content | Promotional banner content is displayed correctly without visual defects | Failed |
| HOME-005 | Verify the customer support chat widget | The chat widget opens, and its main elements are available | Passed |
| HOME-006 | Verify the Back to Top button | Clicking the button scrolls the page back to the top | Passed |
| HOME-007 | Verify delivery, warranty, payment, and return information links | The corresponding information pages or sections open successfully | Passed |
| HOME-008 | Verify social media links on the homepage | Each social media link redirects the user to the corresponding platform | Failed |
| HOME-009 | Verify App Store and Google Play links | The links redirect the user to the corresponding application pages | Passed |

## 5. Product Search

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| SRCH-001 | Search for an existing product by its full name | Relevant products are displayed in the search results | Passed |
| SRCH-002 | Search using a partial product name | Relevant search suggestions or results are displayed | Passed |
| SRCH-003 | Search by product brand and category | Search results display products matching the specified category and brand | Failed |
| SRCH-004 | Search for a non-existing product | An appropriate no-results message is displayed | Passed |
| SRCH-005 | Submit an empty search field | The search is not performed, or the website displays the appropriate behavior | Passed |
| SRCH-006 | Verify search suggestions | Suggestions correspond to the entered search query | Passed |
| SRCH-007 | Search using special characters | The website handles special characters without errors or unexpected behavior | Passed |

## 6. Product Catalog, Filters and Sorting

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CAT-001 | Open a product category | Products are displayed correctly on the category page | Passed |
| CAT-002 | Apply an available product filter | Only products matching the selected filter are displayed | Passed |
| CAT-003 | Apply multiple product filters | Displayed products match all selected filter criteria | Passed |
| CAT-004 | Clear selected filters | The selected filters are removed, and the product list is updated | Passed |
| CAT-005 | Sort products by price in ascending order | Products are sorted from the lowest to the highest price | Passed |
| CAT-006 | Sort products by price in descending order | Products are sorted from the highest to the lowest price | Passed |
| CAT-007 | Navigate through product listing pages or load more products | The next products are loaded or the next page opens correctly | Passed |

## 7. Product Cards on Homepage

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CARD-001 | Verify product card information | Product cards display the product name, image, and current price | Passed |
| CARD-002 | Verify discounted product information | Discounted products display the original price, discount amount, and current price correctly | Passed |
| CARD-003 | Verify product ratings and review counts | Rating and review information is displayed correctly when available | Passed |
| CARD-004 | Click a product card | The corresponding product details page opens | Passed |
| CARD-005 | Add a product to Favorites from its card | The product is added to Favorites, or the user is prompted to sign in | Passed |
| CARD-006 | Add a product to Compare from its card | The product is added to the comparison list | Passed |

## 8. Product Details Page

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| PDP-001 | Open a product details page | The correct product details page opens | Passed |
| PDP-002 | Verify product name and price | The product name and current price are displayed correctly | Passed |
| PDP-003 | Verify product images | Product images load successfully and correspond to the selected product | Passed |
| PDP-004 | Verify product availability information | Product availability information is displayed correctly | Passed |
| PDP-005 | Verify product specifications | Product characteristics and specifications are displayed correctly | Passed |
| PDP-006 | Navigate through the product image gallery | The user can switch between product images successfully | Passed |
| PDP-007 | Verify the product reviews section | Available customer reviews and ratings are displayed correctly | Passed |

## 9. Shopping Cart

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CART-001 | Add a product to the cart | The selected product is successfully added to the shopping cart | Passed |
| CART-002 | Add the same product to the cart again | The product quantity or cart contents are updated according to the website behavior | Passed |
| CART-003 | Increase product quantity | The product quantity and total price are updated correctly | Passed |
| CART-004 | Decrease product quantity | The product quantity and total price are updated correctly | Passed |
| CART-005 | Remove a product from the cart | The selected product is removed successfully | Passed |
| CART-006 | Open an empty shopping cart | An appropriate empty-cart message or state is displayed | Passed |
| CART-007 | Refresh the page after adding a product to the cart | The cart contents remain consistent after refreshing the page | Passed |
| CART-008 | Verify the cart total price | The total price is calculated correctly based on product prices and quantities | Passed |

## 10. Checkout Process

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CHK-001 | Proceed to checkout with a product in the cart | The checkout page or next checkout step opens successfully | Passed |
| CHK-002 | Submit the checkout form with empty required fields | Validation messages are displayed for required fields | Passed |
| CHK-003 | Enter an invalid phone number | The website prevents invalid input or displays an appropriate validation message | Passed |
| CHK-004 | Enter an invalid email format, if email is required | An appropriate validation message is displayed | Passed |
| CHK-005 | Verify available delivery options | Available delivery options are displayed correctly | Passed |
| CHK-006 | Verify available payment options | Available payment options are displayed correctly | Passed |
| CHK-007 | Verify the order total before placing an order | The order total corresponds to the selected products, quantities, and applicable delivery costs | Passed |

## 11. Newsletter Subscription

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| NEWS-001 | Submit the newsletter subscription form with a valid email address | The subscription is processed, and an appropriate confirmation message is displayed | Passed |
| NEWS-002 | Submit the newsletter subscription form with an invalid email address | The website rejects the invalid email address and displays a validation message | Passed |
| NEWS-003 | Submit the newsletter subscription form with an empty email field | The website prevents submission or displays an appropriate validation message | Passed |

## 12. Promotional Sections and Product Carousels

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| PROMO-001 | Navigate through a product carousel using the arrow buttons | The carousel displays the next or previous products correctly | Passed |
| PROMO-002 | Click the Show More button in a product section | Additional products are displayed or the relevant product listing page opens | Passed |
| PROMO-003 | Verify promotional product links | Clicking a promotional product or offer opens the corresponding product or promotion page | Passed |

## 13. Authenticated User Account

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| ACC-001 | Verify the welcome pop-up after successful registration or login | A welcome pop-up is displayed with a personalized greeting and available account actions | Passed |
| ACC-002 | Verify closing the welcome pop-up | Clicking the close button closes the pop-up, and the homepage remains accessible | Passed |
| ACC-003 | Verify the Cabinet menu for an authenticated user | Clicking the Cabinet icon opens a dropdown menu with available account sections | Passed |
| ACC-004 | Verify the My Orders option in the Cabinet menu | Clicking My Orders opens the user's order history page | Passed |
| ACC-005 | Verify user profile information on the account page | The user's name, phone number, and email address are displayed correctly when available | Passed |
| ACC-006 | Verify the empty orders state for a new user | An appropriate empty-state message is displayed when the user has no orders | Passed |
| ACC-007 | Verify the Go Shopping link in the empty orders state | Clicking the link redirects the user to the shopping section or homepage | Passed |
| ACC-008 | Verify the Wallet section in the account menu | Clicking Wallet opens the user's wallet page | Passed |
| ACC-009 | Verify the Favorites section in the account menu | Clicking Favorites / Expected Products opens the corresponding page | Passed |
| ACC-010 | Verify the Bonus History section in the account menu | Clicking Bonus History opens the user's bonus history page | Passed |
| ACC-011 | Verify the Repair section in the account menu | Clicking Repair opens the corresponding repair information or service page | Passed |
| ACC-012 | Verify the Personal Data section in the account menu | Clicking Personal Data opens the user's profile information page | Passed |
| ACC-013 | Verify the Viewed Products section in the account menu | Clicking Viewed Products opens the list of recently viewed products | Passed |
| ACC-014 | Verify the Reviews and Questions section in the account menu | Clicking Reviews and Questions opens the corresponding section | Passed |
| ACC-015 | Verify the logout option in the account page | Clicking Log Out logs the user out and redirects to an appropriate page | Passed |
| ACC-016 | Verify access to the account after logout | After logging out, the user cannot access protected account information without signing in again | Passed |
| ACC-017 | Verify the account session after page refresh | After refreshing the page, the authenticated user remains logged in while the session is valid | Passed |
| ACC-018 | Verify the Cards tab in the Wallet section | Clicking the Cards tab displays the user's saved cards | Not Run |
| ACC-019 | Verify the Coupons tab in the Wallet section | Clicking the Coupons tab displays the user's available coupons | Not Run |
| ACC-020 | Verify the Gift Cards tab in the Wallet section | Clicking the Gift Cards tab displays the user's gift cards | Not Run |
| ACC-021 | Verify the empty state in the Wallet section | An appropriate empty-state message is displayed when the user has no saved cards or coupons | Passed |
| ACC-022 | Verify switching between Wallet tabs | The user can switch between Cards, Coupons, and Gift Cards tabs without errors | Passed |
| ACC-023 | Verify the Favorites tab | Clicking the Favorites tab displays the user's favorite products | Passed |
| ACC-024 | Verify the Expected Products tab | Clicking the Expected Products tab displays the user's expected products | Passed |
| ACC-025 | Verify the empty state in the Favorites tab | An appropriate empty-state message is displayed when the user has no favorite products | Passed |
| ACC-026 | Verify the empty state in the Expected Products tab | An appropriate empty-state message is displayed when the user has no expected products | Passed |
| ACC-027 | Verify creating a new Favorites list | Clicking Create New List opens an interface for creating a new list | Passed |
| ACC-028 | Verify the bonus balance information | The user's current bonus balance and bonus categories are displayed correctly | Passed |
| ACC-029 | Verify the empty state in Bonus History | An appropriate message is displayed when the user has no bonus transactions | Passed |
| ACC-030 | Verify the bonus history information message | The message explaining when bonus history becomes available is displayed correctly | Not Run |
| ACC-031 | Verify the All filter in Communication History | Clicking All displays all available communication records | Passed |
| ACC-032 | Verify the Orders filter in Communication History | Clicking Orders displays only order-related communications | Passed |
| ACC-033 | Verify the Personal filter in Communication History | Clicking Personal displays only personal communications | Passed |
| ACC-034 | Verify the Offers filter in Communication History | Clicking Offers displays only promotional communications | Passed |
| ACC-035 | Verify switching between Communication History filters | The user can switch between all filters without page errors or incorrect content | Passed |
| ACC-036 | Verify the empty state in Communication History | An appropriate empty-state message is displayed when there are no communications | Passed |
| ACC-037 | Verify the repair status search field | The user can enter a repair act number into the search field | Passed |
| ACC-038 | Verify repair status search with a valid act number | The system displays the repair status corresponding to the entered act number | Not Run |
| ACC-039 | Verify repair status search with an invalid act number | The system displays an appropriate message when the entered act number is invalid or not found | Passed |
| ACC-040 | Verify expanding the repair FAQ sections | Clicking an FAQ item expands the corresponding answer | ? |
| ACC-041 | Verify collapsing the repair FAQ sections | Clicking an expanded FAQ item collapses its answer | Passed |
| ACC-042 | Verify the More Questions and Answers button | Clicking the button redirects the user to the additional questions and answers page | Passed |
| ACC-043 | Verify the empty state in Viewed Products | An appropriate empty-state message is displayed when the user has not viewed any products | Passed |
| ACC-044 | Verify the Reviews tab in Reviews and Questions | Clicking Reviews displays the user's submitted reviews | Not Run |
| ACC-045 | Verify the Questions tab in Reviews and Questions | Clicking Questions displays the user's submitted questions | Not Run |
| ACC-046 | Verify the empty state in the Reviews tab | An appropriate message is displayed when the user has not submitted any reviews | Passed |
| ACC-047 | Verify the empty state in the Questions tab | An appropriate message is displayed when the user has not submitted any questions | Passed |

## 14. UI and Responsive Testing

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| RESP-001 | Verify homepage layout at desktop resolution (1440px) | All elements are displayed correctly without unintended overlapping | Passed |
| RESP-002 | Verify homepage layout at tablet resolution (768px) | Content adapts to the viewport without unintended overlapping or horizontal overflow | Passed |
| RESP-003 | Verify homepage layout at mobile resolution (375px) | Main content and interactive elements are displayed correctly without horizontal overflow | Passed |
| RESP-004 | Verify homepage layout at mobile resolution (320px) | Content remains accessible, readable, and usable on a small screen | Passed |
| RESP-005 | Verify product details page layout at tablet and mobile resolutions | Product information and interactive elements adapt correctly to smaller screens | Passed |

## 15. Footer Testing

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| FOOT-001 | Verify footer visibility | The footer is displayed correctly at the bottom of the page | Passed |
| FOOT-002 | Verify footer section headings | All footer section headings are visible and correctly displayed | Passed |
| FOOT-003 | Verify the About the Company link | Clicking the About the Company link redirects the user to the corresponding page | Passed |
| FOOT-004 | Verify the content of the About the Company page | The content is displayed correctly without visual defects | Passed |
| FOOT-005 | Verify the Shops link | Clicking the Shops link redirects the user to the corresponding page | Passed |
| FOOT-006 | Verify the content of the Shops page | The content is displayed correctly without visual defects | Passed |
| FOOT-007 | Verify the Contacts link | Clicking the Contacts link redirects the user to the corresponding page | Passed |
| FOOT-008 | Verify the content of the Contacts page | The content is displayed correctly without visual defects | Passed |
| FOOT-009 | Verify the Press Center link | Clicking the Press Center link opens the corresponding page | Passed |
| FOOT-010 | Verify the content of the Press Center page | The content is displayed correctly without visual defects | Failed |
| FOOT-011 | Verify the Job at COMFY link | Clicking the Job at COMFY link opens the corresponding page | Passed |
| FOOT-012 | Verify the content of the Job at COMFY page | The content is displayed correctly without visual defects | Passed |
| FOOT-013 | Verify the Safety and Precautions link | Clicking the Safety and Precautions link opens the corresponding page | Passed |
| FOOT-014 | Verify the content of the Safety and Precautions page | The content is displayed correctly without visual defects | Passed |
| FOOT-015 | Verify the Tender link | Clicking the Tender link opens the corresponding page | Passed |
| FOOT-016 | Verify the content of the Tender page | The content is displayed correctly without visual defects | Passed |
| FOOT-017 | Verify the For Partners link | Clicking the For Partners link opens the corresponding page | Passed |
| FOOT-018 | Verify the content of the For Partners page | The content is displayed correctly without visual defects | Passed |
| FOOT-019 | Verify the Product Catalog link | Clicking the Product Catalog link opens the corresponding page | Passed |
| FOOT-020 | Verify the content of the Product Catalog page | The content is displayed correctly without visual defects | Passed |
| FOOT-021 | Verify the COMFY Helps link | Clicking the COMFY Helps link opens the corresponding page | Passed |
| FOOT-022 | Verify the content of the COMFY Helps page | The content is displayed correctly without visual defects | Passed |
| FOOT-023 | Verify the Bonus Program link | Clicking the Bonus Program link opens the corresponding page | Passed |
| FOOT-024 | Verify the content of the Bonus Program page | The content is displayed correctly without visual defects | Passed |
| FOOT-025 | Verify the Gift Cards link | Clicking the Gift Cards link opens the corresponding page | Passed |
| FOOT-026 | Verify the content of the Gift Cards page | The content is displayed correctly without visual defects | Passed |
| FOOT-027 | Verify the Services, Subscriptions and Software link | Clicking the Services, Subscriptions and Software link opens the corresponding page | Passed |
| FOOT-028 | Verify the content of the Services, Subscriptions and Software page | The content is displayed correctly without visual defects | Passed |
| FOOT-029 | Verify the Credit and Payment in Installments link | Clicking the Credit and Payment in Installments link opens the corresponding page | Passed |
| FOOT-030 | Verify the content of the Credit and Payment in Installments page | The content is displayed correctly without visual defects | Passed |
| FOOT-031 | Verify the Trade-In link | Clicking the Trade-In link opens the corresponding page | Passed |
| FOOT-032 | Verify the content of the Trade-In page | The content is displayed correctly without visual defects | Passed |
| FOOT-033 | Verify the Service Contracts link | Clicking the Service Contracts link opens the corresponding page | Passed |
| FOOT-034 | Verify the content of the Service Contracts page | The content is displayed correctly without visual defects | Passed |
| FOOT-035 | Verify the Non-Cash Accounts link | Clicking the Non-Cash Accounts link opens the corresponding page | Passed |
| FOOT-036 | Verify the content of the Non-Cash Accounts page | The content is displayed correctly without visual defects | Passed |
| FOOT-037 | Verify the Payment link | Clicking the Payment link opens the corresponding page | Passed |
| FOOT-038 | Verify the content of the Payment page | The content is displayed correctly without visual defects | Passed |
| FOOT-039 | Verify the Customer Assistance Center link | Clicking the Customer Assistance Center link opens the corresponding page | Passed |
| FOOT-040 | Verify the content of the Customer Assistance Center page | The content is displayed correctly without visual defects | Passed |
| FOOT-041 | Verify the Find an Order link | Clicking the Find an Order link opens the corresponding page | Passed |
| FOOT-042 | Verify the content of the Find an Order page | The content is displayed correctly without visual defects | Passed |
| FOOT-043 | Verify the Terms of Delivery link | Clicking the Terms of Delivery link opens the corresponding page | Passed |
| FOOT-044 | Verify the content of the Terms of Delivery page | The content is displayed correctly without visual defects | Passed |
| FOOT-045 | Verify the Exchange and Return of Item link | Clicking the Exchange and Return of Item link opens the corresponding page | Passed |
| FOOT-046 | Verify the content of the Exchange and Return of Item page | The content is displayed correctly without visual defects | Passed |
| FOOT-047 | Verify the Warranty link | Clicking the Warranty link opens the corresponding page | Passed |
| FOOT-048 | Verify the content of the Warranty page | The content is displayed correctly without visual defects | Passed |
| FOOT-049 | Verify the Terms of Use link | Clicking the Terms of Use link opens the corresponding page | Passed |
| FOOT-050 | Verify the content of the Terms of Use page | The content is displayed correctly without visual defects | Passed |
| FOOT-051 | Verify customer support phone numbers | Phone numbers are visible and clickable | Passed |
| FOOT-052 | Verify customer support email | Clicking the email address opens the default email application with the correct recipient | Passed |
| FOOT-053 | Verify footer social media links | Each social media icon redirects the user to the corresponding platform | ? |
| FOOT-054 | Verify footer newsletter subscription form | The email field and subscription button are displayed and functional | Passed |
| FOOT-055 | Verify footer newsletter form validation | Invalid email addresses are rejected, and appropriate validation messages are displayed | Passed |
| FOOT-056 | Verify footer layout on Desktop | Footer elements are correctly aligned and do not overlap | Passed |
| FOOT-057 | Verify footer layout on Tablet | Footer elements are displayed correctly at tablet screen widths | Passed |
| FOOT-058 | Verify footer layout on Mobile | Footer elements are displayed correctly at mobile screen widths | Passed |
| FOOT-059 | Verify footer text alignment and spacing | Text elements have appropriate margins, padding, and spacing | Passed |
| FOOT-060 | Verify footer link hover states | Footer links display the correct hover effect when the cursor is moved over them | Passed |
| FOOT-061 | Verify footer content after page refresh | Footer content remains correctly displayed after refreshing the page | Passed |

---

## Test Execution Notes

### Test Status Definitions

- **Passed:** The actual result matches the expected result.
- **Failed:** The actual result does not match the expected result.
- **Blocked:** The test cannot be executed because of an external limitation.
- **Not Run:** The test has not been executed yet.

### Important Notes

- All test results must be based on actual test execution.
- Any identified defects should be documented separately in the `Bug Reports` folder with supporting screenshots and reproduction steps.
- Some tests may depend on website functionality, user authorization, or available test data.
- If a feature is unavailable, record the reason rather than assuming that the test has passed.
- No real orders or payments will be completed during testing.

### Test Environment

- **Website:** https://comfy.ua/
- **Browser:** Google Chrome
- **Operating System:** Windows 11 Pro
- **Testing Type:** Manual Testing
- **Responsive Viewports:** Desktop (1440px), Tablet (768px), Mobile (375px and 320px)
