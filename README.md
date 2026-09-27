# Portfolio: Manual QA Testing & Jira Defect Lifecycle Simulation

This repository showcases real-world manual testing methodologies, boundary constraint evaluations, and structural bug logging practices using **Demo Blaze** as the target web application and **Jira Cloud** for issue tracking.

## 🛠️ Environment Configuration & Architecture
*   **Target Application Under Test (AUT):** [Demo Blaze Website](https://demoblaze.com)
*   **Defect Management Infrastructure:** Jira Software (Agile Kanban Board/Jira Software Bug Tracking)
*   **Testing Stratagems:** Explatory Testing, Form Validation Verification, Boundary Value Testing

---

## 📊 Agile Scrum/Kanban Pipeline Status
Below is a snapshot highlighting the current sprint tracking iteration context inside Jira, emphasizing item prioritization matrices and state categorizations.

![Jira Sprint Overview](screenshots/jira_board.png)

---

## 🐛 Documented Bug Reports (Jira Extracts)

### 1. Missing Sign-Up Field Constraints
*   **Tracking ID:** BRP-01
*   **Severity:** Medium | **Priority:** Low
*   **Summary:** Submission of empty forms relies on basic unstyled browser notifications rather than clear inline context warnings.
*   **Visual Logs:**
    ![Jira Ticket UI](screenshots/signup.png)
    ![App UI Error](/ticket_errors/sign_up.png)

### 2. Contact Message Omission Error
*   **Tracking ID:** BRP-02
*   **Severity:** High | **Priority:** Medium
*   **Summary:** Message request form configuration processes blank text parameter packets as successful completions.
*   **Visual Logs:**
    ![Jira Ticket UI](screenshots/message_body.png)
    ![App UI Error](/ticket_errors/message.png)
### 3. Product Catalog Specification Gap
*   **Tracking ID:** BRP-03
*   **Severity:** Low | **Priority:** Low
*   **Summary:** Device index information layout omits essential system SKU/Inventory serialization code identification blocks.
*   **Visual Logs:**
    ![Jira Ticket UI](screenshots/constraints.png)
    ![App UI Error](/ticket_errors/product.png)

### 4. Empty Cart Summary State Nullification
*   **Tracking ID:** BRP-04
*   **Severity:** Medium | **Priority:** Medium
*   **Summary:** Total price calculation variables default to an empty string on unpopulated product tables.
*   **Visual Logs:**
    ![Jira Ticket UI](screenshots/empty_cart.png)
    ![App UI Error](/ticket_errors/cart.png)
