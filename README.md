# Food Delivery Web Application

## Overview

This Food Delivery Web Application is built using a Microservice Architecture, leveraging technologies such as Nest.js, GraphQL, Next.js, NextUI, Framer Motion, Prisma, TypeScript, and Node.js. The goal of this application is to provide a seamless and efficient platform for users to order and receive food from various restaurants.

## Technologies Used

- **Nest.js**: A powerful Node.js framework for building scalable and maintainable server-side applications.
- **GraphQL**: A query language for APIs that enables efficient communication between the client and the server.
- **Next.js**: A React-based framework for building server-side rendered and static web applications.
- **NextUI**: A UI framework for Next.js that enhances the development of beautiful and responsive user interfaces.
- **Framer Motion**: A motion library for React that makes it easy to create fluid animations.
- **Prisma**: A modern database toolkit that simplifies database access with type-safe queries.
- **TypeScript**: A superset of JavaScript that adds static typing for improved developer productivity.
- **Node.js**: A JavaScript runtime for server-side development.

## Features

- **Microservice Architecture**: The application is designed as a set of loosely coupled microservices, each responsible for a specific functionality (e.g., user authentication, order processing, restaurant management).
- **GraphQL API**: The application exposes a GraphQL API to provide a flexible and efficient way for clients to interact with the server.
- **Server-side Rendering (Next.js)**: Next.js is used for server-side rendering, providing better performance and SEO optimization.
- **UI Components (NextUI)**: The application's user interface is built using NextUI components, ensuring a consistent and responsive design.
- **Smooth Animations (Framer Motion)**: Framer Motion is utilized to create smooth and engaging animations to enhance the user experience.
- **Database Integration (Prisma)**: Prisma is used for type-safe database access, simplifying data management and ensuring data consistency.
- **TypeScript for Type Safety**: TypeScript is employed to add static typing, reducing errors and improving code maintainability.
- **Node.js for Server-side Logic**: Node.js is used for server-side logic to handle requests, process business logic, and communicate with databases.

## Getting Started

### Prerequisites

- Node.js and npm installed
- Docker for running microservices in containers
- Prisma CLI for database migrations

### Installation

1. Clone the repository: `git clone https://github.com/SQLSorcerer/food-delivery-app.git`
2. Install dependencies for the frontend: `cd client && npm install`
3. Install dependencies for the backend: `cd server && npm install`
4. Set up and migrate the database: `cd server && prisma migrate dev`
5. Start the microservices: `docker-compose up -d`
6. Start the frontend application: `cd client && npm run start`


## Folder Structure

- **client**: Contains the frontend code built with Next.js, NextUI, and Framer Motion.
- **server**: Houses the backend services developed using Nest.js, GraphQL, Prisma, and TypeScript.

## Contributing

Contributions are welcome! If you would like to contribute to the project, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- The development team would like to express gratitude to the open-source community for the tools and libraries used in building this application.
- Special thanks to [contributors](CONTRIBUTORS.md) who have actively participated in the development of this project.
