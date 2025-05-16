# Checkout Module - Test Cases

| TC ID  | Title                      | Description                       | Pre-Conditions     | Test Steps                      | Input Data                            | Expected Result                               | Status |
|--------|----------------------------|---------------------------------|--------------------|--------------------------------|--------------------------------------|----------------------------------------------|--------|
| TC001  | Successful Checkout         | Complete order with valid data   | User logged in     | Fill address and pay            | Valid address and payment details    | Order confirmation shown                       | Pass   |
| TC002  | Empty Cart Checkout         | Attempt checkout with empty cart | User logged in     | Go to checkout with empty cart  | N/A                                  | Show error “Cart is empty”                     | Pass   |
