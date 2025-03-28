# Family Travel Tracker

A web application that helps families track their travel experiences across different countries. Each family member can have their own profile and track their visited countries.

## Features

- Create multiple user profiles with custom colors
- Track visited countries for each user
- View total number of countries visited
- Interactive world map visualization
- Easy country search and addition

## Prerequisites

- Node.js
- PostgreSQL database
- npm (Node Package Manager)

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```
DB_USER=your_database_user
DB_HOST=your_database_host
DB_NAME=your_database_name
DB_PW=your_database_password
```

## Database Setup

The application requires a PostgreSQL database with the following tables:

- `users`: Stores user information (id, name, color)
- `countries`: Contains country information (country_code, country_name)
- `visited_countries`: Tracks which countries each user has visited (country_code, user_id)

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd family-travel-tracker
```

2. Install dependencies:
```bash
npm install
```

3. Set up your environment variables in `.env`

4. Start the server:
```bash
node index.js
```

The application will be available at `http://localhost:3000`

## Usage

1. Create a new user profile by clicking the "Add New User" button
2. Enter your name and choose a color for your profile
3. Search for countries you've visited using the search bar
4. View your visited countries on the interactive map
5. Switch between different user profiles to track each family member's travels

## Technologies Used

- Express.js
- PostgreSQL
- EJS (Embedded JavaScript)
- Node.js

<img width="1433" alt="Screenshot 2025-03-07 at 3 09 01 PM" src="https://github.com/user-attachments/assets/3f28e68e-5c16-42c6-a1d3-deb8293a5737" />
