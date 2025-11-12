## Collections
- Changes on collection handling
- Design upgrades for collections
- Slight refreshes

### Key Points:
- Work with Raqui on revamps for themes
- Needs some changes on featured product lines on banners
- Go through all the brand pages and see which product lines might have photos that can't be procured
- Consistency between Shop by Category collection page and collection banner (aesthetics)
- See if reduction on search bar categories would be viable
- Coming Soon collection needs a new image / snippet / description / banner

---
## Tariff Excel
- Assistance with Tariff Excel

---
## Shopify
- In-house insurance not showing at checkout page

### What seems to be happening?
- This was caused by the Checkout Buddy block not being enabled for ShopPay checkout, hence only appearing on regular checkouts but not on ShopPay checkouts. This was already fixed by enabling the option for ShopPay page.

---
## Wishlist Functionality
- Needs troubleshooting

### What seems to be happening?
- It seems that it's caused by the inventory policy whether to continue selling when out of stock, affecting the functionality of the 'Add to Cart' button. The button ignores whether it's a 'Coming Soon' item, as long as the app sees that it's available for pre-ordering on the inventory policy settings, it will enable the 'Add to Cart' button. This info is confirmed by the Swym/Wishlist Plus team. Looking further in the troubleshooting, the affected Coming Soon product did have a PO Cap tag in it.
- (Further context: I found it odd that there were items that didn't have the Sold Out banner after I did the fixes for the staff accounts -- this is how I came up with the conclusion before testing it out)
- What I did is to add 'Coming Soon' to the exempted tags for the PO Cap automation in Mechanic, just so the automation won't put the product into pre-order even if it has the Coming Soon tag. For the affected product(s), we can manually deny their continue inventory policy options for now, then let Mechanic do its job on the inventory policy once we lift the Coming Soon tag. Tag and automation tests were done on Raqui's test product to prove this functionality with the addition of the Coming Soon tag on our end.


---
# Draft

Hi Keval!! Need some of your feedback on these to-dos:
- HATCH Dropdown Phone
- Wishlist - Trouble shooting
- EDD Site Audit

--- 

# Needs to be Updated:

## Fountain Pens

**Original**:
  ```
  IMAGE_2023-05-31_16_02_53
  ```

 **New**:
 ```
 01 - Fountain Pens
 ```
 
## Ink Bottles

**Original**:
  ```
IMAGE_2023-05-31_15_59_10
  ```

 **New**:
 ```
07 - Ink Bottles
 ```
 
## Notebook & Paper

**Original**:
  ```
 IMAGE_2023-05-31_16_03_38
  ```

 **New**:
 ```
13 - Notebooks & Paper
 ```
 
## Ballpoint Pens

**Original**:
  ```
IMAGE_2023-05-31_16_01_28
  ```

 **New**:
 ```
03 - Ballpoint Pens
 ```
 
## Leather Goods

**Original**:
  ```
IMAGE_2023-05-31_16_00_44
  ```

 **New**:
 ```
19 - Leather Goods
 ```

---

# Day Progress - 100325

Day summary:
- Locks for Gravitas and Tono & Lims collections + reversions to-do
- Updated 'New on Site' HTML tags for both collections; double-checked navi placements
- Double-checked with Sam regarding photo progress for banners (can only start updating on backend once she has progress with photos)
- SEO audit cleanups (tag hierarchy fixes, dead inlink fixes, and redirects)
- Double-checked Google Tag setup done by Raqui, seems correct -- reached out to Shopify team again (and Google if need be, when advised)