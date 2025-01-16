# User App Documentation


# User App Deployment
- https://wisdom-peak-analytics-assignment.vercel.app/.

## Project Overview
This project is a user management application built using React. It incorporates dark mode functionality, user context for data sharing, and various pages for user listing and detailed views.

### Directory Structure
```plaintext
src/
├── components/
│   ├── Navbar.jsx
│   ├── UserCard.jsx
├── context/
│   ├── UserContext.jsx
├── pages/
│   ├── HomePage.jsx
│   ├── UserDetailPage.jsx
├── App.jsx
└── index.css
```

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Shiakh0112/wisdom-peak-analytics-assignment-.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

---

## Features

### 1. Dark Mode Toggle
- Implemented in `App.jsx`.
- Smooth transition effects when toggling dark mode.
- Button to toggle between light and dark themes available in the `Navbar` component.

### 2. Pagination
- Implemented on the `HomePage.jsx`.
- Allows users to navigate through a paginated list of users with "Previous" and "Next" buttons.

### 3. User Search and Sorting
- Users can search by name using an input field.
- Sorting feature allows sorting by name in ascending (A-Z) or descending (Z-A) order.

### 4. User Listing
- Users are displayed as cards (`UserCard.jsx`) with hover and responsive effects.
- Includes user details such as name, email, and city.

### 5. User Details Page
- Each user has a detailed view available on `UserDetailPage.jsx`.
- Includes fields such as name, email, phone, company, and website.
- "Go Back" button for easy navigation.

---

## File Details

### 1. `App.jsx`
- Manages global dark mode state using `useState`.
- Configures routing for `HomePage` and `UserDetailPage`.



### 2. `Navbar.jsx`
- Contains the dark mode toggle button.
- Styled with gradient background and responsive shadow effects.

### 3. `UserCard.jsx`
- Displays individual user information.
- Responsive and interactive hover effects.

### 4. `HomePage.jsx`
- Includes search, sorting, and pagination functionalities.
- Dynamically filters and sorts user data before rendering.

### 5. `UserDetailPage.jsx`
- Fetches detailed user information based on the user ID.
- Includes a "Go Back" button for navigation.

### 6. `UserContext.jsx`
- Provides user data using React Context API.

### 7. `index.css`
- Configured with Tailwind CSS for utility-first styling.

---

## Final Adjustments
- Ensure Tailwind CSS is installed and properly configured.
- Verify all components are mobile-responsive.
- Add additional error handling for user data fetching and rendering.

---

## Dependencies
- React
- React Router DOM
- Tailwind CSS

---

## Future Enhancements
- Add API integration for real-time user data.
- Implement additional filters (e.g., by location or company).
- Enhance animations for a more interactive UI.

---

