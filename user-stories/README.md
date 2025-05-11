# User Stories Documentation

This folder contains the `user-stories.md` file which documents the core user stories derived from the use case diagram of the Airbnb Clone backend project. This directory contains user stories derived from the [use case diagram](../use-case-diagram/use-case-diagram.png). 

Each user story outlines a functional interaction between a system actor (guest, host, or admin) and the backend system. These stories form the foundation for developing the system's features.

## Structure
- `user-stories.md`: Prioritized list of user stories.
- `README.md`: Overview of the user stories process.

## Acceptance Criteria
1. **Guest Registration**  
   - Users can sign up via email or OAuth.  
   - JWT tokens are issued upon successful registration.  

2. **Property Search**  
   - Filters include location, price range, and amenities.  
   - Results load in <2 seconds.  

3. **Secure Booking & Payment**  
   - Integrate Stripe/PayPal APIs.  
   - Prevent double bookings via date validation.  

4. **Listing Management**  
   - Hosts can upload property photos.  
   - Edit history is logged for audit purposes.  

5. **Review System**  
   - Reviews require a completed booking.  
   - Hosts receive email notifications for new reviews.  

6. **Admin Oversight**  
   - Admin dashboard shows user activity logs.  
   - Suspicious accounts can be flagged or deactivated.  
