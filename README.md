# Inverso NextJS Application

This is the Inverso web application. It is built on top of [**Next**](https://nextjs.org), it uses [**AuthJS**](https://authjs.dev/) for authentication and [**Apollo**](https://www.apollographql.com/) as a mean to communicate with the backend.

## Technologies Used

- [Next.js](https://nextjs.org) - React framework for building server-side rendered and statically generated applications
- [AuthJS](https://authjs.dev/) - Authentication library for Next.js applications
- [Apollo](https://www.apollographql.com/) - GraphQL implementation for communication with the backend
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework for rapid UI development
- [TypeScript](https://www.typescriptlang.org/) - Typed superset of JavaScript for improved developer experience

## Getting Started
1. Clone the repository
2. Rename the `.env.example` file to `.env.development` (the latter being ignored by git to avoid secret leaks) and fill in all the required environment variables.
3. Install dependencies:
    ```bash
    yarn install
    ```
4. Run the development server:
    ```bash
    yarn dev
    ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.