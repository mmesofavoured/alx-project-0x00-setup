# ALX Project 0x00 – Next.js Setup

This project was scaffolded using `npx create-next-app@latest`.

## Tech Stack
- Next.js (Pages Router)
- TypeScript
- Tailwind CSS
- ESLint

## Setup Instructions
1. Install dependencies:
   npm install

2. Run the development server:
   npm run dev -- -p 3000

3. Open the app in your browser:
   http://localhost:3000


## Basic Routing

This project uses the Next.js Pages Router.
- `/` → Home page
- `/landing` → Landing page
- `/about` → About page

## Components

Reusable UI components are stored in the `components` directory.
- Card component
- Pill component

Assets such as images are stored under `public/assets/images`.

## Using Components

The `Card` component is reused multiple times on the Landing page to demonstrate
component reusability and modular UI design in React and Next.js.

## Typing Components

TypeScript interfaces are used to strongly type component props.
The `PillProps` interface is defined in the `interfaces` directory and reused
across components to ensure type safety and reusability.


## Button Component

A reusable Button component was created that accepts dynamic text and styles
via props. Multiple button sizes and shapes are rendered on the Landing page
to demonstrate component reusability and flexibility.
