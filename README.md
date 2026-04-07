# pharmacy-erp-qa-automation-framework
# Pharmacy ERP QA Automation Framework
This project gave me strong experience in business workflow validation, distributed system testing, API automation, schema validation, and release regression strategy, which directly aligns with enterprise QA roles.


A production-style **QA automation showcase project** for a Pharmacy / Medical ERP platform.

This project demonstrates **functional testing, API automation, UI automation, and end-to-end workflow validation** for real-world pharmacy business scenarios such as authentication, inventory, order billing, GST validation, invoice generation, and stock reconciliation.

It is designed as a portfolio-ready framework for **QA Engineer, SDET, Functional QA, and Automation QA roles**.

---

## Project Goal
The objective of this framework is to validate critical workflows in a medical retail ERP system:

- secure login and role-based access
- medicine inventory lifecycle
- batch and expiry validation
- order creation and billing
- GST and tax calculations
- payment workflows
- invoice PDF generation
- sales and stock reports
- end-to-end pharmacy order lifecycle

---

## Tech Stack
- **Playwright**
- **TypeScript**
- **APIRequestContext** for API automation
- **Page Object Model (POM)**
- **JSON Schema Validation**
- **GitHub Actions** for CI
- **Allure Reports**
- **Faker** for test data

---

## Test Coverage
### Functional Testing
- Login validation
- Invalid credential scenarios
- Medicine stock management
- Expiry medicine restrictions
- Invoice total verification
- GST slab validation
- Discount rules
- Payment success/failure
- Refund and return flow

### API Automation
- Auth token generation
- Create medicine
- Update stock
- Create order
- Validate invoice response
- Report summary APIs

### UI Automation
- Login page
- Dashboard navigation
- Billing flow
- Stock management
- Reports filters

### End-to-End Testing
**Hero scenario:**

Login → Search medicine → Add to cart → Validate stock → Apply GST → Payment → Generate invoice → Verify stock deduction

└── README.md
