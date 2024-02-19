---
title: "Fineract - Advanced payment allocation"
slug: fineract-advanced-payment-allocation
speakers:
 - Adam Saghy
time_start: 2024-06-04 14:40:00
time_end: 2024-06-04 15:10:00
tracks:
 - Fintech
---

Since the first repayment strategy got introduced, many followed, but there was one thing common in them:
 
 They were hard coding the allocation rules for each transaction type.
 
 
 
 By introducing - part of the 1.9.0 release - the "Advanced payment allocation" the idea was to have a repayment strategy which was:
 
 - Supporting dynamic configuration of the allocation rules for transaction types
 
 - Supporting configuration of more fine-grained allocation rules for future installments
 
 - Supporting reprocessing of transactions and charges in chronological order
 
 
 
 Capabilities
 
 - Allocation strategy:
 
  - Horizontal (installment level)
 
  - Vertical (loan level)
 
 
 
 - Allocation rules:
 
  - Based on due time type (past due, due, in advance)
 
  - Based on due balance type (principal, penalty, fee, interest)
 
 
 
 - Transaction level configuration
 
 - Fine-grained in advance payment allocation rules
 
 
 
 During the session the audience will get a better insight about the business requirements - which lead to introducing this new repayment strategy mechanics into Fineract - and learn its provided functionalities.