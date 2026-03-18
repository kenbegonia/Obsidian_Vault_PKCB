# Project Management Role Exam

You are assigned as the project manager for the development of an online food ordering and delivery software system. After meeting with the product owner, you were given a set of high level requirements needed for the minimum viable product (MVP). These are:

1. Customer Ordering: Allow users to browse local restaurants and place an order for delivery.
2. Driver Logistics: Provide a basic system for a third-party driver to accept, track, and complete a delivery.
3. Secure Payment: Process payments securely and reliably, supporting major credit cards and GCash.
4. Restaurant Management Portal: Allow partner restaurants to view incoming orders and mark them as ready for pickup.

Task 1: Choose one of the above 4 high level requirements, and break it down into granular, user stories that can be shared with the development team (to create development timeline estimates). For the user stories, use the following structure:

AS A [User Role], I WANT TO [Goal], SO THAT [Reason/Benefit]

### As the product manager is not available to support you during this exercise, please use your imagination in clearly defining precisely how the requirements would work.

_Answer_: I'm choosing the first option: **Customer Ordering**.

- As a customer, I want to be able to see a homepage with the list of recommended restaurants so that I can see which restaurants are near me right now.
- As a customer, I want to be able to search restaurants so that I can see the list of restaurants according to my tastes and specificity.
- As a customer, I want to be able to see somewhere how far is that restaurant from me so that I can visualize how much time the restaurant needs to take the food to me.
- As a customer, I want to be able to see the operating hours so that I know when would be the last call for the restaurant.
- As a customer, I want to be able to see the menu of the restaurant so that I can see the choices of food they have.
- As a customer, I want to be able to see the availability status of the menu entries so that I can easily know which menu items are and are not available.
- As a customer, I want to be able to see the food entry photos so that I can easily set my own expectations for the food's quality.
- As a customer, I want to be able to see all reviews of the restaurant so that I can make an informed decision on my quality expectations for the food and service.
- As a customer, I want to be able to add the food items to my cart so that I know that I have a list of food that I want to order in the restaurant.
- As a customer, I want to be able to adjust the quantity of the food item to order so that I can order food en masse when the need arises.
- As a customer, I want to be able to send a note for the food I'll be adding to cart so that I can send specific requests and allergy considerations to the restaurant.
- As a customer, I want to be able to see the cart so that I know the tentative list of the food I'm about to order.
- As a customer, I want to be able to edit my order on the cart view so that I can do last minute changes on my order when the need arises.
- As a customer, I want to be able to order my cart so that the food I wanted can be ordered and delivered to me.

### Task 2: Create a set of acceptance criteria for one of the user stories created in the above Task 1. Again, use your imagination to clearly define how the system should work.

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

Story: "As a customer, I want to be able to see the cart so that I know the tentative list of the food I'm about to order."

Acceptance Criteria:
- There should be a viewable Cart page that contains all of the food entries that was added. 
- The Cart page should be accessible via a button within the restaurant page. 
- Correct entries from the correct restaurant should be present.

Story: "As a customer, I want to be able to order my cart so that the food I wanted can be ordered and delivered to me."

Acceptance Criteria:
- There should be a checkout button on the Cart page.
- Checking out should direct the user to the order confirmation page.
- The order confirmation page should correctly output the ordered food items and the subtotal.

### Task 3: Explain what are Non-Functional Requirements (NFRS). What would be some expected Non-Functional Requirements (NFRs) for the system described above?

Answer: In my own words, non-functional requirements are requirements on how the system should behave and work, and not on what the system can provide (features). Some examples of NFRs for the above stories are the load time of the restaurant lists, the usability of UX flow for the restaurant-to-cart pages, and if the orders are secure, on the backend side.

### Questions:
#### 1. A member of the development team is consistently delivering less than expected output on sprint cycles. What steps would you take to try to improve the performance of that developer?

Answer: I would first have a one-on-one assessment with the affected member to determine any and all causes of why they’re delivering outputs below expectations. After the root cause(s) have been identified, we can then make a performance improvement plan that can involve the domain lead and gathering resources if needed, with an assessment after a certain timeframe, so that the project can still move forward while the issue of the member gets resolved.

#### 2. One senior developer has been less engaged with the project recently. They are a key member of the team, as only they understand some of the core underlying technology related to a key part of the system. What actions would you take in a situation like this? 

Answer: For this one, besides knowing the root cause of why the senior developer is underperforming, I also want to give them a heads-up that their efforts still matter and how valuable their activities are based on past metrics that they’ve achieved. I would then make a performance improvement plan for them to achieve certain goals within a time period, and I would also try to negotiate with the stakeholders on which resources we can allocate to help the senior developer achieve their PIP goals.

#### 3. The product owner keeps pushing for adding new features into the software. At the same time, you've heard feedback from the development team that there are underlying issues in the code that should be addressed, related to security and code documentation. How would you try to balance the push for new features, vs feedback from the team about potential code issues?

Answer: I would first make a change control plan which involves assessing the impact of changes to the constraints (budget, timeline, and scope) and their alignment to the business goals, and any and all changes moving forward shall be subject for approval by me and the other stakeholders to ensure that new features are according to the business goals. 

For the feedback, there would be also an assessment regarding its impact to the business and project goals, and how it would also affect the project constraints. The findings would then be relayed to all the stakeholders for us to make an informed decision if we can still continue development or whether we should escalate the feedback to the executives and/or the client.

#### 4. Describe some ways that you've used in the past to motivate team members to give their best effort in their work every day.

Answer: My own way in the past to motivate team members is to celebrate small wins, and let them know that their efforts are appreciated by the project team. The small wins can be determined by looking at the project progress and activity on the PM tool, based on different key performance indices.