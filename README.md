Food Stall Discovery Platform
1. App Concept
Build a 

Food Stall Discovery Platform consisting of a mobile app for users (iOS and Android) and a companion website. The core purpose is to bridge the gap between "Foodies" seeking local food stalls and the stall owners who provide unique culinary experiences.




The app's main competitive advantage and 

most critical feature is its reliance on real-time, owner-verified information. It must solve the problem of outdated or inaccurate data found on general food platforms.



2. Target Audiences
The platform will serve two distinct user types:


Users ("Foodies"): People actively looking for diverse, local, and authentic food options. They need a reliable and easy way to discover stalls, see what's currently open, find their location (especially for mobile stalls), and filter by specific criteria like cuisine or dietary needs.




Stall Owners: Often small, independent, and sometimes mobile vendors who need a very simple, low-cost digital tool to manage their online presence and communicate essential real-time updates to customers (e.g., today's location, current open/closed status, daily hours, days off).



3. Core Features (Minimum Viable Product - MVP)
User-Facing App & Website Features:

Stall Discovery: An interactive map and a filterable list view showing food stalls based on the user's current location.


Powerful Search & Filtering: Users must be able to search by stall name or cuisine and filter results by:

Food type/Cuisine

Dietary needs (e.g., Vegan,non-veg - tagged by the owner)

Distance

User rating

Crucially: A "Currently Open" toggle based on the owner's real-time status.


Detailed Stall Profiles: Each stall should have a profile page with:

Photos and a business description.

Cuisine type and menu highlights.

User ratings and reviews.

Real-time operational status ("Open," "Closed") and location, updated directly by the owner.


User Accounts: Allow users to create a basic profile to save their favorite stalls.

Stall Owner-Facing Features (Web Portal):
This needs to be an extremely simple and intuitive web-based portal, designed for non-technical users.


Profile Management: A secure login where owners can edit their business name, description, food type, upload photos, and list menu items.


Real-Time Status Control: A simple dashboard with easy-to-use controls to instantly:

Update their current location (either by dropping a pin on a map or using device GPS).

Set their operating hours for the current day.

Toggle their status between "Open for Business" and "Closed for the Day."

Announce upcoming days off.


Basic Dashboard: Show simple metrics like profile views.

4. Key User Flow Example
User Journey: A user opens the app. It automatically shows nearby food stalls on a map. She filters for "Tacos" and "Currently Open." She sees a food truck's profile, checks its menu highlights and user reviews, and sees on the map that it is currently located at a park two blocks away.

Owner Journey: The owner of the taco truck arrives at the park. He logs into the owner portal on his phone, taps "Update Location" which uses his phone's GPS to set his new spot, sets his hours to "11 AM - 7 PM," and flips a switch to "Open." The entire process takes less than 30 seconds.

5. Design and UX/UI Notes
The design should be clean, modern, and intuitive, with a mobile-first approach.


The owner's portal must prioritize simplicity over features. It should require minimal taps to perform the most important action: updating location and status.

Incorporate accessibility features like high-contrast colors and screen reader compatibility.

6. Future Scalability
The platform's architecture should be built to support future enhancements, most importantly an 

integrated delivery and ordering system with payment gateway integration.

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
