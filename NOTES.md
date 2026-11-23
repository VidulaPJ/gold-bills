## Gold Bills 2.4.6

- **More careful reading of item rows.** A row's gold value must now match weight × rate closely, so a gross weight that happens to come near the row's amount is no longer taken as the gold value (this mis-read a ring with stones).
- **Printed rates with a ₹ sign** ("22K: ₹12,850.00") are now read even when the phone reads the ₹ as "%", so each item is checked against the bill's own 22K or 18K rate, not one worked out from 24K.

Also in 2.4.5: feedback form; 2.4.3: each item checked against the rate printed on its bill.
