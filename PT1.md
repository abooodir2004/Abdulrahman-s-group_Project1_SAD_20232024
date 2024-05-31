## 5.1 Current Business Process (Scenarios, Workflow)

### Scenarios:

#### Customer Order Processing:

1.  Customer places an order via the online platform.
2.  The system checks inventory for the requested items.
3.  If items are in stock, the system processes the payment.
4.  An order confirmation is sent to the customer.
5.  The warehouse is notified to prepare the order for shipment.
6.  The order is shipped, and a shipping confirmation is sent to the customer.

#### Inventory Management:

1.  Inventory levels are monitored in real-time.
2.  When stock levels fall below a predefined threshold, a restock order is generated.
3.  The warehouse receives new stock and updates the inventory levels in the system.

#### Customer Support:

1.  Customers can submit support tickets via the online platform.
2.  Support tickets are logged and assigned to a support agent.
3.  The support agent resolves the issue and updates the ticket status.
4.  The customer is notified of the resolution.

### Workflow:

#### Order Processing Workflow:

1.  **Start:**  Customer places an order.
2.  **Check Inventory:**  System verifies stock availability.
3.  **Payment Processing:**  System processes the payment.
4.  **Order Confirmation:**  System sends confirmation to the customer.
5.  **Order Preparation:**  Warehouse prepares the order.
6.  **Shipping:**  Order is shipped.
7.  **End:**  Shipping confirmation is sent to the customer.

#### Inventory Management Workflow:

1.  **Start:**  Monitor inventory levels.
2.  **Stock Check:**  System checks stock levels.
3.  **Restock Order:**  Generate restock order if needed.
4.  **Stock Update:**  Update inventory levels.
5.  **End:**  Inventory levels are updated.

#### Customer Support Workflow:

1.  **Start:**  Customer submits a support ticket.
2.  **Ticket Logging:**  System logs the ticket.
3.  **Ticket Assignment:**  Assign ticket to a support agent.
4.  **Issue Resolution:**  Support agent resolves the issue.
5.  **Ticket Update:**  Update ticket status.
6.  **End:**  Notify customer of resolution.

----------

## 5.2 Functional Requirements (Input, Process, and Output)

### Customer Order Processing:

-   **Input:**  Customer order details, payment information.
-   **Process:**  Validate order, check inventory, process payment, notify warehouse.
-   **Output:**  Order confirmation, inventory update, shipping notification.

### Inventory Management:

-   **Input:**  Current stock levels, restock thresholds.
-   **Process:**  Monitor stock levels, generate restock orders, update stock.
-   **Output:**  Updated inventory records, restock notifications.

### Customer Support:

-   **Input:**  Support ticket details, customer information.
-   **Process:**  Log ticket, assign to agent, resolve issue, update ticket status.
-   **Output:**  Ticket status updates, resolution notifications.

----------

## 5.3 Non-Functional Requirements (Performance and Control)

### Performance:

-   The system must handle up to 10,000 simultaneous users without performance degradation.
-   Order processing time should not exceed 2 seconds.
-   Inventory updates should be reflected in real-time.

### Control:

-   The system must have robust security measures to protect customer data.
-   Access to the system should be controlled via role-based access control (RBAC).
-   Regular backups of the system data must be performed daily.
-   The system should be compliant with industry standards such as PCI-DSS for payment processing.
