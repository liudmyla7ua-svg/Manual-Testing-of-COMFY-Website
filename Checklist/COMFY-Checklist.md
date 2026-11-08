# COMFY Website — Test Checklist

**Project:** COMFY E-commerce Website  
**Website:** https://comfy.ua/  
**Testing Type:** Manual Testing  
**Environment:** Google Chrome / Windows  
**Test Status:** In Progress

## 1. Homepage and Navigation

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-001 | Open the homepage | Homepage loads successfully | Not Run |
| CH-002 | Verify website logo | Clicking the logo redirects to the homepage | Not Run |
| CH-003 | Header navigation links | Each navigation link redirects the user to the correct page | Not Run |
| CH-004 | Navigate to a product category | Correct category page opens | Not Run |
| CH-005 | Verify footer links | Links redirect to the correct pages | Not Run |
| CH-006 | Verify city selection | The list of available cities is displayed, and the selected city is shown correctly |	Not Run |
| CH-007 | Verify language switching | The website content is displayed in the selected language |	Not Run |
| CH-008 | Verify product search by product name | Relevant search results are displayed |	Not Run |
| CH-009 | Verify search with a non-existent product name |	A clear message indicating that no results were found is displayed |	Not Run |
| CH-010 | Verify promotional banners |	Clicking a promotional banner redirects the user to the corresponding promotion or page | Not Run |
| CH-011 | Verify closing the sign-in pop-up | The pop-up is closed, and the main page content remains accessible | Not Run |
| CH-012 | Verify the newsletter subscription form | The email field validates the email format, and invalid email addresses are rejected | Not Run |
| CH-013 | Verify the customer support chat widget | The chat widget opens, and its main elements are available | Not Run |

## 2. Product Search

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-006 | Search for an existing product | Relevant products are displayed | Not Run |
| CH-007 | Search using a partial product name | Relevant search suggestions or results appear | Not Run |
| CH-008 | Search using a non-existing product name | An appropriate no-results message is displayed | Not Run |
| CH-009 | Submit an empty search field | Search is not performed or appropriate behavior is displayed | Not Run |
| CH-010 | Verify search suggestions | Suggestions correspond to the entered query | Not Run |

## 3. Product Catalog, Filters and Sorting

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-011 | Open a product category | Products are displayed correctly | Not Run |
| CH-012 | Apply an available product filter | Only matching products are displayed | Not Run |
| CH-013 | Apply multiple filters | Products match all selected filter criteria | Not Run |
| CH-014 | Clear selected filters | All applicable products are displayed again | Not Run |
| CH-015 | Sort products by price ascending | Products are sorted from lowest to highest price | Not Run |
| CH-016 | Sort products by price descending | Products are sorted from highest to lowest price | Not Run |

## 4. Product Details Page

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-017 | Open a product details page | Correct product information is displayed | Not Run |
| CH-018 | Verify product name and price | Product name and price are displayed correctly | Not Run |
| CH-019 | Verify product images | Product images load successfully | Not Run |
| CH-020 | Verify product availability information | Availability information is displayed | Not Run |
| CH-021 | Verify product specifications | Product characteristics are displayed correctly | Not Run |

## 5. Shopping Cart

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-022 | Add a product to the cart | Product is successfully added to the cart | Not Run |
| CH-023 | Add the same product again | Cart quantity or contents update according to the website behavior | Not Run |
| CH-024 | Increase product quantity | Quantity and total price are updated correctly | Not Run |
| CH-025 | Decrease product quantity | Quantity and total price are updated correctly | Not Run |
| CH-026 | Remove a product from the cart | Product is removed successfully | Not Run |
| CH-027 | Open an empty cart | Appropriate empty-cart message is displayed | Not Run |

## 6. Checkout Process

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-028 | Proceed to checkout with a product in the cart | Checkout page or next checkout step opens | Not Run |
| CH-029 | Submit checkout form with empty required fields | Validation messages are displayed | Not Run |
| CH-030 | Enter an invalid phone number | Validation prevents invalid input or displays an error | Not Run |
| CH-031 | Enter invalid email format, if email is required | Validation message is displayed | Not Run |
| CH-032 | Verify available delivery options | Available delivery options are displayed | Not Run |
| CH-033 | Verify available payment options | Available payment options are displayed | Not Run |

## 7. UI and Responsive Testing

| ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| CH-034 | Verify homepage layout at desktop resolution | Elements are displayed correctly without unintended overlap | Not Run |
| CH-035 | Verify product page layout at tablet and mobile resolutions | Content adapts to the viewport without horizontal overflow | Not Run |

## Test Execution Notes

- **Pass:** Actual result matches the expected result.
- **Fail:** Actual result does not match the expected result.
- **Blocked:** Test cannot be executed because of an external limitation.
- **Not Run:** Test has not been executed yet.

All test results must be based on actual execution.

No real orders or payments will be completed during testing.
