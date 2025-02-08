# Marketplace-Builder-hackathon-2025
FurniNest - Furniture Marketplace

Project Overview

FurniNest is a modern and responsive e-commerce platform designed for selling furniture online. The project utilizes Next.js, Tailwind CSS, Sanity, Stripe, and Clerk to provide a seamless shopping experience, including product listings, a shopping cart, and user authentication.

Project Timeline & Activities

Day 1: Planning & Setup

Defined project scope and objectives for an online furniture marketplace.

Set up the Next.js project with Tailwind CSS for styling.

Created initial folder structure for components, pages, and assets.

Designed homepage layout using Figma as a reference.

Day 2: API Integration & Data Fetching

Configured Sanity.io as the headless CMS for managing product data.

Integrated Sanity API into the project.

Fetched and displayed product data dynamically on the frontend.

Implemented product detail pages using dynamic routing in Next.js.

Day 3: Shopping Cart & Authentication

Integrated Stripe for handling payments.

Implemented Clerk for user authentication and account management.

Developed the shopping cart functionality using React state management.

Added the ability to add and remove items from the cart.

Day 4: Deployment & Optimization

Deployed the project using Vercel.

Performed Lighthouse testing to optimize Performance, Accessibility, SEO, and Best Practices.

Improved website speed and ensured responsiveness across different devices.

Conducted final testing to ensure a smooth user experience.

Folder Structure

FurniNest/
│── public/                  # Static assets (logos, icons, images)
│── src/
│   ├── components/          # Reusable React components
│   │   ├── Navbar.tsx       # Navigation bar
│   │   ├── Footer.tsx       # Footer section
│   │   ├── ProductCard.tsx  # Product display component
│   │   ├── Cart.tsx         # Shopping cart component
│   ├── pages/
│   │   ├── index.tsx        # Homepage
│   │   ├── product/         # Product detail pages (Dynamic Routing)
│   │   ├── cart.tsx         # Shopping cart page
│   │   ├── checkout.tsx     # Checkout page with Stripe integration
│   ├── sanity/              # Sanity CMS configuration
│   │   ├── schema.ts        # Sanity schema for products
│   ├── styles/              # Tailwind CSS custom styles
│── .env.local               # Environment variables for API keys
│── next.config.js           # Next.js configuration file
│── package.json             # Project dependencies
│── README.md                # Project documentation

Deployment

Hosted on Vercel:[ Live Demo](https://furni-nest-sfih.vercel.app/)

GitHub Repository: [Repo Link](https://github.com/FATIIMA29/FurniNest)

Future Improvements

Implement search and filtering functionality for products.

Add user reviews and ratings.

Improve accessibility and best practices score further.

add admin and user portal.

integrate AI chatbot

Developed by: Fatima Akif

