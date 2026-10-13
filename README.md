# Assignment #4 — Facade Pattern. 
Topic: online shop checkout (Option C). 
`OrderFacade.placeOrder(...)` hides four subsystem classes: 
`InventoryService`, `PaymentService`, `ShippingService`, `NotificationService`. 

## Files (src/) 
| File | Role |
|---|---|
| InventoryService.java | Subsystem – stock and prices |
| PaymentService.java | Subsystem – card charge |
| ShippingService.java | Subsystem – shipping, tracking number |
| NotificationService.java | Subsystem – e-mails |
| OrderFacade.java | Facade |
| OrderException.java | Exception shown to the client |
| Main.java | Client |