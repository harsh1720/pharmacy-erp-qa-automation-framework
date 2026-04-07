# Medical ERP QA Showcase Project (GitHub Portfolio)

## Project Idea

Build a **QA automation showcase project for a Pharmacy / Medical ERP system** based on real business workflows.

* Functional QA
* Automation QA
* API Testing
* Microservices QA
* ERP / Retail / Healthcare domain QA

---

## Business Modules to Cover

### 1) Authentication

* Login
* JWT token validation
* Role-based access (Admin, Cashier, Pharmacist)
* Session expiry

### 2) Inventory

* Add medicine
* Update stock
* Batch number
* Expiry date validation
* Negative stock prevention
* Low stock alert

### 3) Orders & Billing

* Create order
* Add multiple medicines
* Discount validation
* GST calculation
* Invoice generation
* Payment success/failure

### 4) Returns

* Return sold medicine
* Stock rollback
* Refund workflow

### 5) Reports

* Daily sales
* GST summary
* Inventory aging
* Expiry medicines report

---

## Best Tech Stack for Showcase

### UI + API Automation

* **Playwright + TypeScript**
* APIRequestContext for backend validation
* Faker for test data
* Allure reports
* GitHub Actions CI

### Optional Add-ons

* Docker
* Newman collection
* JSON schema validation
* Mock microservices events

---

## Recommended Folder Structure

```text
pharmacy-erp-qa-automation-framework/
│
├── tests/
│   ├── api/
│   │   ├── auth.spec.ts
│   │   ├── inventory.spec.ts
│   │   ├── orders.spec.ts
│   │   └── reports.spec.ts
│   │
│   ├── ui/
│   │   ├── login.spec.ts
│   │   ├── billing.spec.ts
│   │   └── stock-management.spec.ts
│   │
│   └── e2e/
│       └── full-order-lifecycle.spec.ts
│
├── pages/
├── utils/
├── test-data/
├── schemas/
├── reports/
├── .github/workflows/
└── README.md
```

---

## Killer End-to-End Scenario

This should be your **hero test case**.

### Full Pharmacy Lifecycle

```text
Login → Search medicine → Add to cart → Validate stock → Apply GST → Payment → Generate invoice → Verify PDF → Validate stock deduction → Send notification
```

This one test alone makes your project look enterprise-grade.

---

## Advanced QA Features That Impress Recruiters

### 1) Contract Testing

Validate order response against JSON schema.

### 2) Data Integrity Checks

* DB state validation (mock JSON/file)
* invoice totals = item totals + GST

### 3) Parallel Execution

Run API suites in parallel.

### 4) Retry Logic

Handle flaky network failures.

### 5) Reporting

* Allure trend reports
* failed screenshots
* API logs
* trace viewer

---

## Complete README.md (Use This in GitHub)

````md
# Pharmacy ERP QA Automation Framework

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

---

## Project Structure
```text
pharmacy-erp-qa-automation-framework/
│
├── tests/
│   ├── api/
│   ├── ui/
│   └── e2e/
│
├── pages/
├── utils/
├── fixtures/
├── test-data/
├── schemas/
├── reports/
├── .github/workflows/
├── playwright.config.ts
├── package.json
└── README.md
````

---

## How to Run

### Install dependencies

```bash
npm install
```

### Run all tests

```bash
npx playwright test
```

### Run API tests

```bash
npx playwright test tests/api
```

### Run UI tests

```bash
npx playwright test tests/ui
```

### Run E2E suite

```bash
npx playwright test tests/e2e
```

### Open HTML report

```bash
npx playwright show-report
```

---

## CI Pipeline

This project includes GitHub Actions for:

* pull request validation
* smoke regression
* nightly E2E execution
* report artifact upload

---

## Business Value

This framework simulates testing for a real **medical shop ERP ecosystem**, focusing on:

* accuracy of medicine stock
* billing correctness
* compliance through GST validation
* stable release confidence
* prevention of production leakage

---

## Why This Project Matters

This portfolio project reflects real enterprise QA capabilities:

* test strategy thinking
* business workflow validation
* microservice-friendly API testing
* regression automation
* CI/CD integration
* scalable framework design

---

## Future Enhancements

* database validation layer
* contract testing with schemas
* visual regression for invoices
* performance smoke checks
* Dockerized test execution
* test data factories

```

---
