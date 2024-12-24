# Netflix GPT

An AI-powered OTT platform that recommends movies based on user preferences and browsing history. Built with React, Redux, Tailwind CSS, and TMDB API to provide a seamless user experience with multilingual support and advanced search capabilities.

---

## Features

### Home Page (Unauthenticated Users)
- Interactive homepage for users who are not signed in.
- Includes features like trending movies, showcases, and suggestions.

### Sign In / Sign Up Page
- **Sign In Form**: Allows existing users to authenticate themselves.
- **Sign Up Form**: Enables new users to create an account.

### Browse Page (Authenticated Users)
- Dynamic **Navbar** for navigation.
- **Showcase** section displaying featured content.
- **Trending** movies list.
- **Movies Suggestions** powered by Netflix GPT AI.
- **Movies List**: Multiple categorized lists of movies fetched from the TMDB API.
- **Search** functionality for browsing movies.

### Netflix GPT AI
- Provides personalized movie recommendations using AI.
- Seamlessly integrates suggestions based on search and user preferences.

---

## Technologies Used

### Frontend
- **React.js**: Component-based UI library for building the application.
- **Tailwind CSS**: Utility-first CSS framework for styling.

### State Management
- **Redux**: Efficient state management for handling data across the app.

### Backend Integration
- **TMDB API**: Fetches movie data dynamically for listings and suggestions.

### Other Libraries
- **Formik**: Form validation and error handling.
- **useRef & useNavigate Hooks**: Enhanced navigation and input handling.

---

## Key Functionalities

- **Multilingual Search Bar**: 
  - Built with memoization to reduce unnecessary server calls and improve performance.
  - Supports searching for movies in multiple languages.

- **Form Validations**:
  - Validates input fields using **Formik**.
  - Error handling is efficiently managed with the **useRef** hook.

- **Page Navigation**:
  - Implemented using the **useNavigate** hook for seamless transitions between pages.

- **Movie Fetching**:
  - Integrated the **TMDB API** to fetch and display movie data.
  - Managed state efficiently with the **Redux Store**.

---

## Setup and Installation

### Prerequisites
Make sure you have the following installed on your system:
- Node.js
- npm or yarn

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/netflix-gpt.git
   ```

2. Navigate to the project directory:
   ```bash
   cd netflix-gpt
   ```

3. Install dependencies:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

4. Create a `.env` file in the root directory and add your TMDB API key:
   ```env
   REACT_APP_TMDB_API_KEY=your_api_key_here
   ```

5. Start the development server:
   ```bash
   npm start
   ```
   or
   ```bash
   yarn start
   ```

6. Open your browser and visit:
   ```
   http://localhost:3000
   ```
