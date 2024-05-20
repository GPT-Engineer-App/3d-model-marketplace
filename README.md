# 3d-model-marketplace

Build an eCommerce website for selling 3D models, similar to 3dsky.org, using Next.js with the App Router, TypeScript (TSX format), and Tailwind CSS. The site should be fully responsive and have a modern UI. It will include functionalities such as a bottom navbar, footer, shopping cart, user authentication, and payment integration.Project Requirements:Frameworks and Languages:Next.js: Utilize the App Router for routing.TypeScript: Ensure all components and pages are typed using TypeScript (TSX format).Tailwind CSS: Implement Tailwind CSS for styling.Page Structure:Home Page: Showcase featured 3D models, categories, and latest additions.Product Listing Page: Display a list of 3D models with filtering and sorting options.Product Detail Page: Detailed view of a 3D model with images, description, and purchase options.Cart Page: Display items added to the shopping cart with options to update quantities or remove items.Checkout Page: User information, shipping details, and payment integration.User Authentication Pages: Sign up, log in, and profile management pages.Components:Bottom Navbar: Navigation links to home, categories, cart, and user profile.Footer: Links to about us, contact, privacy policy, and social media icons.Shopping Cart: Component to add, remove, and update the quantity of items.User Authentication: Sign up, log in, and logout functionalities using NextAuth or another authentication provider.Payment Integration: Integrate a payment gateway (such as Stripe) for processing transactions.Additional Functionalities:Responsive Design: Ensure the site is fully responsive and works well on mobile, tablet, and desktop devices.Modern UI: Use Tailwind CSS to create a clean and modern user interface.Search Functionality: Allow users to search for 3D models.Filter and Sort: Filter and sort models by category, price, popularity, etc.User Reviews and Ratings: Enable users to leave reviews and ratings for models.Wishlist: Allow users to save models to a wishlist for future purchases.Technical Implementation:Setup and Configuration:Initialize a new Next.js project with TypeScript.Install and configure Tailwind CSS.Authentication:Set up NextAuth or another authentication provider for user sign-up and login functionalities.Create authentication pages and protect certain routes.State Management:Use React Context or a state management library (such as Redux) to manage global state (e.g., cart items, user session).API Integration:Set up APIs for fetching 3D model data, user authentication, and handling payments.Use Next.js API routes for server-side operations.Payment Gateway:Integrate Stripe or another payment gateway for handling transactions on the checkout page.Deployment:Prepare the application for deployment, ensuring all environment variables and configurations are set.

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/3d-model-marketplace.git
cd 3d-model-marketplace
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
