# Talking Points
- 
## Done
- [Copyright infringement](https://mail.google.com/mail/u/1/#all/FMfcgzQhVhhQwcDNLkPTDlkDdBBdncQg) — scrap
- [Discount stacking](https://app.basecamp.com/5539926/buckets/31105695/todos/10038232664#__recording_10185445687) — do discount audits to check stacking logic
- [Increase shipping rates](https://app.basecamp.com/5539926/buckets/31105695/todos/10038298268#__recording_10042542275) 
- [EDD: Flow for Marketing](https://app.basecamp.com/5539926/buckets/31105695/todos/9953111055) — any update?
- [Combine Orders automation](https://app.basecamp.com/5539926/buckets/31085772/messages/10096618357) — any opinion? ok to implement?
- [Component Report automation](https://app.basecamp.com/5539926/buckets/31085772/messages/10118908092) — any opinion? ok to implement?
 
---

## Needs Action
- [Copyright infringement](https://mail.google.com/mail/u/1/#all/FMfcgzQhVhhQwcDNLkPTDlkDdBBdncQg) — what shall we do?
- [Discount stacking](https://app.basecamp.com/5539926/buckets/31105695/todos/10038232664#__recording_10185445687) — let's look at how discount stacking works now!
- [Increase shipping rates](https://app.basecamp.com/5539926/buckets/31105695/todos/10038298268#__recording_10042542275) — for countercheck
- [EDD: Flow for Marketing](https://app.basecamp.com/5539926/buckets/31105695/todos/9953111055) — any update?
- [Combine Orders automation](https://app.basecamp.com/5539926/buckets/31085772/messages/10096618357) — any opinion? ok to implement?
- [Component Report automation](https://app.basecamp.com/5539926/buckets/31085772/messages/10118908092) — any opinion? ok to implement?
- [Multiple product discounts](https://app.basecamp.com/5539926/buckets/31105695/todos/10038232664#__recording_10046848225) — demonstrate to kk how stacking works
- [HATCH color themes](https://app.basecamp.com/5539926/buckets/47134021/todos/10167232741#__recording_10190244630) — for viewing

---

# Action Items for Codebugs and/or KK
- Discount stacking: check discounts on what would work with which


---

## How The New Discount Stacking Works
- Old discount "stacking" worked on the same line item by determining both discounts and whoever has the better offer wins and gets offered to the customer
- New line-item discount stacking works almost exactly what we wanted 
- Similar to the discount strategies we've had by stacking native codes and Script-based automatic discounts

### Enabling the New Discount System
- Tag discounts that we want to stack with the same tag. 
- Open the discount(s) → Combinations → Allow product discounts → Multiple per product, then use the tags from the first point on the discount to stack with.

### Order of Discount Stacking
- Percentage + Fixed Amount: percentage is applied first, then the flat discount amount  
- Percentage + Percentage: these discounts compound instead of adding together with the bigger percentage getting applied first
