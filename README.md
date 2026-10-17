# TrendFusion — Fashion & Styling Platform

TrendFusion is a React web app for browsing fashion collections, viewing product details, and exploring outfit and avatar styling features.

## Features

- Browse the home page and shop men's, women's, and kids' collections.
- View product details and manage a shopping cart.
- Visit the login and signup page.
- Create an avatar for the weekly styling contest.
- Share outfit ideas and interact with the community page.

## Tech stack

- React 18 and Create React App
- React Router for page navigation
- Redux Toolkit and React Redux for shared state
- React Toastify and React Hot Toast for notifications
- Tailwind CSS configuration is included in the project

## Requirements

- Node.js and npm

## Run locally

```bash
git clone https://github.com/OfficialRaushanKumar/TREND_FUSION-Fashion_and_Styling_Platform.git
cd TREND_FUSION-Fashion_and_Styling_Platform
npm install
npm start
```

The development server opens at [http://localhost:3000](http://localhost:3000).

## Available scripts

| Command | Description |
| --- | --- |
| `npm start` | Start the development server. |
| `npm run build` | Create an optimized production build in `build/`. |
| `npm test` | Run the Create React App test suite. |

## Project structure

```text
public/                 Static files and app metadata
src/
  componenets/           Shared UI components and fashion assets
  Context/               Shopping context
  pages/                 Shop, product, cart, login, contest, and community pages
  redux/                 Redux store and feature slices
  App.js                 Routes and application layout
  index.js               Application entry point
```

## Notes

Product catalog data and community posts are currently held in the frontend. The app does not include a backend service or persistent user authentication.
