# Meeting Notes
- Discounted gift cards: Runs from Wednesday 12:01AM EST to Thursday 4:00AM EST (or until site closure)

## Sales Target
- `Gross Sales`: $500,000

---

# New Products
- [x] Sailor Ink Bottle (50ml) - Manyo IV - Limited Edition (2024)
- [x] Sailor Ink Bottle (20ml) - Dipton Fragrance
- [x] Sailor Fountain Pen - TUZU Glassy #1 - Limited Edition (2025)
- [x] Sailor Fountain Pen - 1911 Profit Jr Akita & Shiba - Shiba Inu Jr - Special Edition (2025)
- [x] Sailor Fountain Pen - Naginata Togi Ebonite Mouko - Limited Edition (2024) - Last One
- [ ] Endless Stationery Ink Bottle (45ml) - Alchemy
- [x] Endless Stationery Ink Bottle (45ml) - Alchemy Obsidian
- [x] Lochby Venture Pouch
- [x] Nahvalur (Narwhal) Fountain Pen - 365 Anniversary - Limited Edition (2025)
- [x] Monteverde Fountain Pen - Regatta Sport - Santorini
- [x] Diplomat Fountain Pen - XO Triple 5 - Racing Green - Limited Edition (2025)
- [x] Troublemaker Ink Bottle (60ml) - 2025 Release
- [x] Pelikan Fountain Pen - Souverän M600 Art Collection #2 - Rudi Rother - Special Edition (2025)
- [ ] Diplomat Fountain Pen - Aero Funky - Special Edition (2025)
- [x] Colorverse Ink Bottle (15ml) - 2026 Red Horse - Special Edition (2026)

---

## Online Food Delivery App

Features I want to see:
- [x] List of restaurants near me
- [x] Search bar for restaurants
- [x] See how far is that restaurant from me
- [x] Operating hours of restaurants
- [x] Online menu of the restaurant
- [x] Menu availability
- [x] Photos of the food in the menu
- [x] Reviews
- [x] Add to Cart functions
- [x] Adjustable order quantity functions
- [x] Custom request messaging for food
- [x] Cart view
- [x] Order editing on Cart view
- [x] Delivery fee options
- [ ] Cart subtotal
- [ ] Order placement button
- [ ] Order confirmation view

---

# Acceptance

Story: "As a customer, I want to be able to see a homepage with the list of recommended restaurants so that I can see which restaurants are near me right now."

Acceptance Criteria:
- The homepage should return the list of restaurants based on user proximity.
- The list of restaurants should also return an approximate distance value.

Story: "As a customer, I want to be able to search restaurants so that I can see the list of restaurants according to my tastes and specificity."

Acceptance Criteria:
- The search results should return a list that approximately matches the search keyword.
- The first five results should contain exact matches to the search keyword.

Story: "As a customer, I want to be able to see somewhere how far is that restaurant from me so that I can visualize how much time the restaurant needs to take the food to me."

Acceptance Criteria:
- The restaurant page should have the approximate distance UI element based from the user’s location.

Story: "As a customer, I want to be able to see the operating hours so that I know when would be the last call for the restaurant."

Acceptance Criteria:
- The restaurant page should have a small UI element that includes the operating hours of the restaurant.

Story: "As a customer, I want to be able to see the menu of the restaurant so that I can see the choices of food they have."

Acceptance Criteria:
- The restaurant page should return a list of the food items that the restaurant contains.

Story: "As a customer, I want to be able to see the availability status of the menu entries so that I can easily know which menu items are and are not available."

Acceptance Criteria:
- The food item entries on the menu view of the restaurant page should be interactable if available. 
- The unavailable food item entries on the restaurant page should not be interactable and is greyed out for visual cues.

Story: "As a customer, I want to be able to see the food entry photos so that I can easily set my own expectations for the food's quality."

Acceptance Criteria:
- The restaurant owners should be able to upload food photos for the menu.
- The customers should be able to view the uploaded photos on the restaurant page.
- A thumbnail should be present when viewing the food entries.

Story: "As a customer, I want to be able to see all reviews of the restaurant so that I can make an informed decision on my quality expectations for the food and service."

Acceptance Criteria:
- Customers should be able to go to another page that contains the restaurant reviews.

Story: "As a customer, I want to be able to add the food items to my cart so that I know that I have a list of food that I want to order in the restaurant."

Acceptance Criteria:
- There should be an “Add to Cart” button present when viewing the food entry page.
- The food entry should be added to the Cart without any problems.

Story: "As a customer, I want to be able to adjust the quantity of the food item to order so that I can order food en masse when the need arises."

Acceptance Criteria:
- There should be a plus and minus button on the food entry page.
- Item quantity should be present on the food entry page. 
- Adding or subtracting using the buttons should update the quantity number.

Story: "As a customer, I want to be able to send a note for the food I'll be adding to cart so that I can send specific requests and allergy considerations to the restaurant."

Acceptance Criteria:
- A text entry field should be present on the food entry page.
- Users should be able to input text on the text field. 
- Users should be able to view the inputted note on the Cart page.

Story: "As a customer, I want to be able to order my cart so that the food I wanted can be ordered and delivered to me."

Acceptance Criteria:
- There should be a checkout button on the Cart page.
- Checking out should direct the user to the order confirmation page.
- The order confirmation page should correctly output the ordered food items and the subtotal.