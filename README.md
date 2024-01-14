# Next.js NextAuth.js Demo Project

This is a simple demo project built with Next.js and NextAuth.js to showcase authentication functionality using popular providers.

## Features

- **Authentication:** Demonstrates user authentication using NextAuth.js.
- **GitHub and Google Providers:** Includes examples of authentication with GitHub and Google.
- **Protected Routes:** Illustrates how to protect routes that require authentication.
- **Session Management:** Shows how to manage user sessions.

## Getting Started

### Prerequisites

- Node.js (>=14.0.0)
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ritace7/nextauth.git


2. Navigate
   ```bash
   cd nextjs-nextauth-demo

3. Install dependencies:

   ```bash
   npm install
   # or
   yarn install

4. Create a .env.local file in the root directory::

   ```env
  GITHUB_ID=your-github-client-id
  GITHUB_SECRET=your-github-client-secret
  GOOGLE_ID=your-google-client-id
  GOOGLE_SECRET=your-google-client-secret
  NEXTAUTH_SECRET=your-nextauth-secret
  MONGODB_URI=your-mongodb-uri


5. Install dependencies:

   ```bash
   npm run dev
   # or
   yarn dev


