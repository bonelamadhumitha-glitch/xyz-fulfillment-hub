# XYZ Fulfillment Hub

A simple fulfillment management application created for the **XYZ Take-Home Project**.

## Project Overview

XYZ is an e-commerce business that manages its fulfillment process using spreadsheets and shared folders.

As the business grows, this creates several operational problems:

* Difficult to track the status of orders
* Priority orders can be missed
* Inventory may be unavailable in the main warehouse
* Wrong products or variants may be picked
* Packed orders can be misplaced
* Courier pickups can be missed
* Operational problems can be forgotten

The **XYZ Fulfillment Hub** provides a simple interface to make the fulfillment process easier to track and manage.

---

## Problem Understanding

The fulfillment process includes:

**Order Received → Order Processed → Picking → Packing → Staging → Shipping**

The application focuses on improving visibility and reducing mistakes across these steps.

---

## Solution

The Fulfillment Hub brings the important fulfillment activities into one application.

The manager can quickly see:

* Today's orders
* Priority orders
* Orders currently being processed
* Orders ready for shipment
* Completed orders
* Inventory alerts
* Operational issues
* Overall fulfillment progress

Warehouse users can follow the order through the fulfillment workflow.

---

## Key Features

### 1. Dashboard

The dashboard provides an overview of the current fulfillment operation.

It displays:

* Today's orders
* Priority orders
* Orders in picking
* Orders ready to ship
* Completed orders
* Operational alerts
* Fulfillment progress

---

### 2. Priority Order Management

Priority orders are clearly highlighted so that they are easier to identify and process before regular orders.

This helps reduce the possibility of priority orders being mixed with normal orders.

---

### 3. Inventory Management

The application supports two warehouse locations:

* Main Warehouse
* Secondary Warehouse

When inventory is unavailable in the Main Warehouse but exists in the Secondary Warehouse, the required stock can be transferred before picking.

---

### 4. Picking Validation

The picking process requires the warehouse user to select the correct product and variant.

If an incorrect product is selected, the application displays an error.

This helps address the problem of incorrect products or variants being shipped to customers.

---

### 5. Packing

After the correct product is picked, the order proceeds to packing.

The user can confirm the package before moving the order to the next stage.

---

### 6. Courier Selection

The application provides courier options with different:

* Delivery speeds
* Costs
* Pickup times

This allows the user to select a suitable courier for the order.

---

### 7. Staging

After packing, the order moves to the staging area.

The staging area provides visibility into packages that are packed and waiting for courier pickup.

---

### 8. Courier Pickup and Dispatch

The application allows the courier pickup to be simulated.

Once the courier collects the package, the order can be marked as dispatched/completed.

---

### 9. Operational Alerts

Important issues are surfaced through alerts, such as:

* Priority orders requiring attention
* Low inventory
* Inventory availability problems
* Orders waiting for pickup

This helps prevent operational issues from being forgotten.

---

## Fulfillment Workflow

The application follows this workflow:

```text
Order Received
      ↓
Inventory Check
      ↓
Stock Transfer if Required
      ↓
Picking
      ↓
Packing
      ↓
Courier Selection
      ↓
Staging
      ↓
Courier Pickup
      ↓
Dispatch / Completed
```

---

## Sample Data

Because real XYZ store, warehouse and courier systems were not available, the application uses dummy data.

The sample data includes:

* Customer orders
* Priority orders
* Products
* Product variants
* Main Warehouse inventory
* Secondary Warehouse inventory
* Courier options
* Shipping information

The data is designed to demonstrate realistic fulfillment scenarios.

---

## Main Demonstration Scenario

A priority order can be used to demonstrate the complete workflow.

Example:

**Order:** `ORD-1044`

The demonstration covers:

1. Priority order identification
2. Inventory checking
3. Stock transfer from the Secondary Warehouse
4. Product picking
5. Picking validation
6. Packing
7. Courier selection
8. Staging
9. Courier pickup
10. Order completion

---

## Design Decisions

The application was intentionally designed to be simple and easy to understand.

The warehouse team described in the problem statement is experienced but not very comfortable with technology.

Therefore, the interface focuses on:

* Clear status indicators
* Large and visible actions
* Simple navigation
* Visual alerts
* Minimal steps
* Easy-to-understand workflow

Rather than attempting to build a complete warehouse management system, the application focuses on the operational problems that can directly lead to missed, delayed or incorrect shipments.

---

## Technology Used

The prototype was built using:

* **HTML**
* **CSS**
* **JavaScript**

The application uses sample data and does not require real e-commerce, warehouse or courier integrations.

---

## How to Run Locally

### Option 1 — Open directly

1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` in a web browser.

### Option 2 — Using VS Code Live Server

1. Open the project in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.
5. The application will open in your browser.

---

## Project Structure

```text
xyz-fulfillment-hub/
│
├── index.html
└── README.md
```

---

## AI Usage

AI tools were used during development for:

* Brainstorming application ideas
* Translating the problem statement into application features
* HTML, CSS and JavaScript development support
* Debugging
* Improving the user interface
* Documentation and walkthrough preparation

AI suggestions were reviewed and modified based on the requirements of the assessment and the needs of the intended users.

---

## Assessment Deliverables

This repository contains the application created for the XYZ Fulfillment Hub Take-Home Project.

The complete submission also includes:

* Application
* Video walkthrough
* AI usage note

---

## Author

**Bonela Madhumitha**

XYZ Fulfillment Hub — Take-Home Project
