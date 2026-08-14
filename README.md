#  Personal Finance Tracker

##  Overview
An app that will gives you a clear picture of where you are today-and a practical path toward where you want to go.

## Features

Dashboard - Financial snapshot, cash flow, net worth, and alerts  
Transactions - Income and expense organized by category  
Budget - Planned versus actual monthly spending  
Goals - Target amount, deadline, and required contribution  
Accounts - Cash, savings, investments, credit cards, and loans  

## Tech Stack
Frontend: React, TypeScript, Vite, Tailwind CSS, Tanstack Query
Backend: Node.js, TypeScript, Express
Database: PostgresSQL
ORM: Prisma
Testing: Viteest, Supertest, Playwright

## Architecture 
I'm using a modular three-tier web architecture with a sperate frontend, backend API, and PostgresSQL database.
Frontend: responsible for UI and user interaction. React should not know how financial calculations are implemented or how PostgresSQL is structured. It should call the API and display the results.
Backend: should have several internal layers rather than putting everything directly into Expresss routes
## Installation

## Screenshots

## API

## Database

## Testing

