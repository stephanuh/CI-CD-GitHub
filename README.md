# CI/CD Pipeline with GitHub Actions and Render

This repository contains a full-stack application with a CI/CD pipeline implemented using GitHub Actions and Render. The pipeline automatically runs tests when pull requests are made to the develop branch and deploys the application to Render when code is merged to the main branch.

[Deployed application here](https://ci-cd-github-ky54.onrender.com)

## Project Overview

This application is a coding quiz that tests users' knowledge of programming concepts. The CI/CD pipeline ensures that all code changes are tested before being integrated and automatically deployed to production.

### Features

- Full-stack application with React frontend and Node.js/Express backend
- MongoDB database for storing quiz questions and user scores
- Automated testing with Cypress component tests
- Automated deployment to Render

## Technologies Used

- **Frontend**: React, Vite
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Testing**: Cypress (component testing)
- **CI/CD**: GitHub Actions
- **Deployment**: Render

# Setup

1. Clone the repository:
   ```
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run start
   ```