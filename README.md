
# Eventing
### Event Organization Responsive Webapp
#### By **[Harshit Verma](https://github.com/harshit7905)**
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.


# Dependencies(tech-stacks)
****Client-Side Dependencies:****

* @clerk/nextjs: Handles authentication and authorization in the browser.
* @hookform/resolvers: Used for form validation on the client-side.
* @radix-ui/react-*: Libraries for building accessible UI components (all likely used in the browser).
* @stripe/stripe-js: Interacts with Stripe for payment processing on the client-side.
* @uploadthing/react: Enables file uploads in the browser.
* clsx: Utility for managing CSS class names (primarily used in client-side styling).
* lucide-react: Icon library likely used within the user interface.
* react: Core library for building user interfaces.
* react-datepicker: Enables date pickers within the browser.
* react-dom: Renders React components in the browser.
* react-dropzone: Enables drag-and-drop file uploads in the browser.
* react-hook-form: Handles form management and validation on the client-side.
* react-js-pagination: Provides pagination functionality within the browser.
* svix: Possibly used for client-side animations or visual effects.
* tailwind-merge: Utility for Tailwind CSS within the browser.
* tailwindcss-animate: Enables animations using Tailwind CSS on the client-side.
* uploadthing: Library related to file uploads (likely used on the client-side).

****Server-Side Dependencies:****

* mongodb: Driver for interacting with MongoDB databases (server-side).
* mongoose: Object Document Mapper (ODM) for MongoDB, used for data modeling on the server.
* next: Next.js framework for building server-rendered and statically generated web applications.
* query-string: Used for parsing query strings on the server-side (potentially).
* stripe: Library for integrating with Stripe for payments on the server-side (likely for processing payments).
* zod: Used for data validation on the server-side.

### Functioning of the Project
1. Authentication (CRUD)
2. Related and Organized Events
3. Search and Filtering
4. Categories
5. Checkout
6. Payment with Stripe
7. Order with Search

### Database Model Structure

![Eventing_DB_structure](https://github.com/harshit7905/evently/assets/128207336/d86ed86d-9e40-4b0a-a381-d7c680dacb7f)
