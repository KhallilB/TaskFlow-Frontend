# TaskFlow Frontend

Welcome to the frontend repository of TaskFlow, an enterprise task management system. This repository contains the client-side components of the TaskFlow application, built with React, Redux for state management, Styled Components and Tailwind for styling, Storybook for UI components, and Axios for API requests.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Features](#features)
- [UI Components](#ui-components)
- [State Management](#state-management)
- [Deployment](#deployment)
  - [Docker](#docker)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

- Node.js (recommended version: X.X.X)
- npm or yarn package manager
- Backend server (TaskFlow backend) running and accessible

### Installation

Clone this repository:
```sh
git clone https://github.com/KhallilB/taskflow-frontend.git
cd taskflow-frontend
```

Install dependencies:
```sh
npm install
# or
yarn install
```

Configure environment variables:

- Copy .env.example to .env and provide the necessary configuration values.

Run the development server:
```sh
npm run dev
```

## Features
- User authentication and login.
- Dashboard displaying ongoing projects, tasks, and notifications.
- Create, update, and manage projects and tasks.
- Real-time collaboration and chat functionality.
- Interactive reports and analytics dashboards.

## UI Components
- Built with React framework.
- Utilizes Tailwind CSS for styling components.
- Styled Components used for custom styling and theming.
- UI components documented and developed using Storybook.

## State Management
- State managed using Redux for efficient and centralized data handling.
- Centralized store to manage application-wide data and user authentication.

## API Requests
API requests are managed using Axios, providing a clean and convenient way to communicate with the backend.

## Deployment
### Docker
- Dockerize the frontend application for consistent deployment across environments.
- Use Docker Compose for managing multi-container applications.

## Contributions
Contributions are welcome! If you'd like to contribute to the project, please follow the guidelines outlined in the Contributing Guidelines.

## License
This project is licensed under the MIT License.