# User Stories for Airbnb Clone Backend

## 1. User Registration

**As a guest or host, I want to be able to register an account so that I can access the platform and manage my activities.**

### Acceptance Criteria

- A user can sign up with an email and password.
- Secure password storage using hashing algorithms.
- Option to sign up using OAuth providers (e.g., Google, Facebook).

---

## 2. Add Property Listings

**As a host, I want to add property details so that potential guests can view and book my listings.**

### Acceptance Criteria

- Hosts can input property details such as title, description, location, price, amenities, and availability.
- The property is saved in the database and visible to guests in search results.

---

## 3. Search for Properties

**As a guest, I want to search for properties using filters so that I can find accommodations that meet my needs.**

### Acceptance Criteria

- Filters available for location, price range, number of guests, and amenities.
- Pagination for large search result datasets.
- Accurate search results based on filters.

---

## 4. Booking Creation

**As a guest, I want to book a property for specified dates so that I can reserve my stay.**

### Acceptance Criteria

- The booking system validates property availability for the selected dates.
- Double bookings are prevented.
- Booking details are stored and linked to the user and property.

---

## 5. Leave a Review

**As a guest, I want to leave a review for a property after my stay so that other guests can make informed decisions.**

### Acceptance Criteria

- Guests can rate and leave text reviews for a property.
- Reviews are linked to specific bookings to prevent abuse.
- Hosts can view and respond to reviews.

---

## Additional Notes

These user stories represent the core functionalities identified in the use case diagram and will guide the development of the backend system for the Airbnb Clone.
