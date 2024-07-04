# Banking Application

A cross-platform banking application built using Next.js, TypeScript, and JavaScript. This application is designed for both web and mobile use, providing a seamless and secure user experience.

## Features

- **Cross-Platform Compatibility**: Optimized for both web and mobile platforms.
- **Secure Data Management**: Utilizes Appwrite for robust backend and data storage.
- **Bank Integration**: Integrated with Plaid to connect with various bank servers.
- **Real-Time Error Monitoring**: Implemented Sentry for immediate error detection and resolution.
- **User Experience Enhancements**: Responsive design and dark mode support.
- **Performance Optimization**: Lazy loading, code splitting, and optimized image loading.

## Technologies Used

- **Frontend**: Next.js, TypeScript, JavaScript
- **Backend**: Appwrite
- **Bank Integration**: Plaid
- **Error Monitoring**: Sentry
- **Continuous Integration**: GitHub Actions

## Getting Started

### Prerequisites

- Node.js
- npm or yarn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/banking-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd banking-app
    ```
3. Install dependencies:
    ```sh
    npm install
    ```
    or
    ```sh
    yarn install
    ```

### Environment Variables

Create a `.env.local` file in the root of your project and add the following environment variables:

```sh
NEXT_PUBLIC_APPWRITE_ENDPOINT=your-appwrite-endpoint
NEXT_PUBLIC_APPWRITE_PROJECT_ID=your-appwrite-project-id
PLAID_CLIENT_ID=your-plaid-client-id
PLAID_SECRET=your-plaid-secret
SENTRY_DSN=your-sentry-dsn
