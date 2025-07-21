# Insta-Board
# InstaBoard Lab

## About
This is a simple React app that displays user profile cards fetched from the Random User API.  
It includes interactive features like dark mode, email toggle, and infinite load more.

## Features
- Reusable `UserCard` component with props.
- Dynamic user list using Axios (`https://randomuser.me/api/?results=12`).
- "Load More" button to fetch additional users.
- Like button for each card (state managed with `useState`).
- Toggle to show/hide user email.
- **Dark Mode** toggle: changes the theme across all cards dynamically.

## Challenges
The hardest part was implementing **dark mode** — passing the theme state down to each card and updating styles based on it. It wasn’t too hard, but it got me confused at first 😅

## Time Spent
Approximately **8 hours** to finish everything.

## How It Works
- `App.js`: Contains the main theme state and renders `UserList`.
- `UserList.js`: Fetches and manages user data, handles "Load More".
- `UserCard.js`: Displays individual user info with interactivity and dynamic styling.

## Bonus
✅ Dark mode toggle  
✅ Search filter by name

## Setup
1. `npm install`
2. `npm start`

---
Made with ❤️ using React
