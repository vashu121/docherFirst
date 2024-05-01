# My Node.js App with Prisma

This is a simple Node.js application that uses Prisma as the ORM (Object-Relational Mapping) tool for interacting with a database. The application is containerized using Docker, ensuring consistent deployment across different environments.

## Prerequisites

- Node.js (version 16 or higher)
- Docker

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
npm install
npx prisma generate
npm run build
docker build -t my-app .
docker run -p 3000:3000 my-app