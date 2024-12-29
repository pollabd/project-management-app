# Next.js Project Management App

This repository contains a comprehensive Project Management Dashboard application built using a combination of cutting-edge technologies and deployed on AWS. The application provides a seamless user experience and efficient project management tools.

## Features

- **Frontend**: Next.js with Tailwind CSS for styling and Material UI Data Grid for handling complex data presentations.
- **State Management**: Redux Toolkit and Redux Toolkit Query for efficient state management and data fetching.
- **Backend**: Node.js with Express for server-side logic.
- **Database**: PostgreSQL managed with Prisma and monitored using PgAdmin.
- **Authentication**: AWS Cognito for user authentication and management.
- **Serverless Computing**: AWS Lambda for scalable, serverless architecture.

---

## Tech Stack

### Frontend

- [Next.js](https://nextjs.org/) - React-based framework for server-side rendering and static site generation.
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework for fast UI development.
- [Material UI Data Grid](https://mui.com/x/react-data-grid/) - Advanced data grid solution for presenting large datasets.
- [Redux Toolkit](https://redux-toolkit.js.org/) - Simplified state management.
- [Redux Toolkit Query](https://redux-toolkit.js.org/rtk-query/overview) - Optimized data fetching and caching.

### Backend

- [Node.js](https://nodejs.org/) - JavaScript runtime environment.
- [Express.js](https://expressjs.com/) - Web framework for building RESTful APIs.

### Database

- [PostgreSQL](https://www.postgresql.org/) - Relational database for managing application data.
- [Prisma](https://www.prisma.io/) - ORM for seamless database integration.
- [PgAdmin](https://www.pgadmin.org/) - Database management tool for PostgreSQL.

### AWS Services

- [AWS Cognito](https://aws.amazon.com/cognito/) - User authentication and authorization.
- [AWS Lambda](https://aws.amazon.com/lambda/) - Serverless compute service for scalable backend logic.
- [AWS EC2](https://aws.amazon.com/ec2/) - Virtual servers for deployment.
- [AWS RDS](https://aws.amazon.com/rds/) - Managed relational database service for PostgreSQL.

---

## Getting Started

### Prerequisites

- Node.js (v14 or above)
- PostgreSQL
- AWS Account

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/pollabd/project-management-app.git
   cd project-management-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the application locally:
   ```bash
   npm run dev
   ```

---

## Deployment

### AWS Configuration

1. **EC2**:

   - Launch an EC2 instance.
   - Install Node.js and set up the application.

2. **RDS**:

   - Set up a PostgreSQL instance using AWS RDS.
   - Configure the `DATABASE_URL` to point to your RDS instance.

3. **Cognito**:

   - Create a user pool and configure client settings.

4. **Lambda**:
   - Deploy serverless functions for backend logic.

### Deploy Application

1. Build the application:

   ```bash
   npm run build
   ```

2. Start the application:
   ```bash
   npm start
   ```

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contributing

We welcome contributions! Please follow the [Contributing Guidelines](CONTRIBUTING.md).

---

## Acknowledgments

Special thanks to all the open-source tools and libraries that made this project possible!
